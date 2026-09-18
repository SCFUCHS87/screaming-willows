<%\*
const people = \[
"Mitch Hunt",
"Phil Lamczyk",
"Matt Negri",
"Linda Weiner",
"Thomas Culp",
"Steven Fuchs",
"Jeff Birmes"
];

const template = tp.file.find\_tfile("Person Template");

for (const name of people) {
const existing = app.vault.getAbstractFileByPath(name + ".md");
if (!existing) {
await tp.file.create\_new(template, name);
}
}
-%>
All person notes created.
