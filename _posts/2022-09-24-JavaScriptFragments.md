---
toc: true
layout: post
description: Team Members
categories: [JavaScript, Week 6]
title: JavaScript Fragments
---

# Our Group Project Members



<div id="JavaScriptGroup"> 
</div>

 <script>
        
        

    let Group = ["Emaad", "Edwin", "Luka", "jishnu"];
    const table = document.createElement ("table");
    const row = document.createElement ("tr");
    for (let i = 0; i < Group.length; i++) {
    
    
    
        let data = document.createElement ("td");
        let node = document.createTextNode(Group [i]);
        data.appendChild(node);
        row.appendChild(data);
    
    }
    
    table.appendChild(row);
    const div = document.getElementById("JavaScriptTable");
    div.appendChild(table);
    
    
    
    


 
</script>