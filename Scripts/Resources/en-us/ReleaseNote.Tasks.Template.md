{{#forEach this.workItems}} {{#if isFirst}} {{#if (eq (lookup this.fields 'System.WorkItemType') 'Task')}} |{{this.id}}|{{{lookup this.fields 'System.Description'}}}| {{/if}} {{/if}} {{/forEach}}