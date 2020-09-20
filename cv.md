# Halina Kononovich
---
## Contact Info
- Phone: +375295784951
- Email: kononovich1703@gmail.com
---
## Summary
>_My goal is to become a front-end developer, who creates interesting and useful applications for people._ 
---
## Skills 
_HTML, CSS, SCSS, BEM, JS, React.js, MongoDB_

---
## Code example

```js
router.post('/quiz', async (ctx, next) => {
  try {
    const answer = await schema.validateAsync(ctx.request.body);
    db.push(answer);
    ctx.response.body = JSON.stringify({answer: 'Thanks for your answer!'});
  }
  catch (err) { 
    ctx.response.body = JSON.stringify({error: err});
    console.log(err);
  }
});
```
