const express = require('express');
const app = express()
app.listen(3000,()=>{
    console.log('server Starting up at port :3000')
})
app.get("",(req,res)=>{
    res.send("<h1>This is testing</h1>");
})
