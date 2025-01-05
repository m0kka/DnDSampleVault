<%* await tp.file.move("/2-World/History/Events/" + tp.file.title);
const hasTitle = !tp.file.title.startsWith("NewEvent");  
let title;  
let date;
if (!hasTitle) {  
date = await tp.system.prompt("Enter Date (yyyy-mm-dd)");
title = await tp.system.prompt("Enter Event Name");
await tp.file.rename(date + " " + title);
} else {  
title = tp.file.title;  
}_%><% "---" %>
aat-render-enabled: true
timelines:
  - maintimeline
fc-date: <%date%>
fc-end:  <%date%>
fc-category:
  - Miscellaneous Events
fc-display-name:  <%title%>
NoteIcon: journal
obsidianUIMode: preview
tags:
  - event
<% "---" %>

%% The first picture will be displayed in the timeline %%
%% The first few lines of text will be displayed in the timeline %%


TEXT