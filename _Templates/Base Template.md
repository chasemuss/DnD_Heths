<%*
let fileName = await tp.system.prompt("Enter the file name:");
// Remove invalid characters (e.g., /, \, :, etc.) and trim whitespace
fileName = fileName.replace(/[\/\\:]/g, "").trim();
// Optional: Capitalize the first letter of each word
fileName = fileName.replace(/\b\w/g, char => char.toUpperCase());
await tp.file.rename(fileName);%><% "---" %>
title: <% fileName %>
tags: 
 - 
<% "---" %>

# Notes

