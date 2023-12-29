---
creation date: <% tp.file.creation_date() %>
steps: 
sleep: 
mood: 
energy: 
---
# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

[[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').subtract(1, 'd').format('YYYY-MM-DD') %>|<< Yesterday]] | [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').add(1, 'd').format('YYYY-MM-DD') %>|Tomorrow >>]] 


## Today's Tasks

- [ ] to do
- [ ] to do

## Logs

- Log 1
- Log 2

## End of Day Notes

### I'm proud that...

- 

### I'm grateful that...

- 

### Tomorrow, I need to...

- 