# Week 7 - Learning Journal

## Learning Activities & Resources
> Guiding statements/questions: :bulb:
> - If you learned from something, link it!
> - Compare why you chose to learn one thing over the other.
> - Format: `topic` | `Purpose` | `Link`

#### Desired learning outcomes & identified gaps in knowledge:
- [x] Structure PHP sites with `include`
- [x] Use `echo` effectively for HTML output
- [x] Implement `if/else` logic for dynamic content
- [x] Use loops (`for`, `while`, `foreach`) for automation
- [x] Write and use PHP functions with parameters
- [ ] Practise PHP database connection in a local environment for a personal project (future goal)

#### Resources:
1. `PHP Documentation` | `Syntax & functions` | [PHP Manual](https://www.php.net/manual/en/)
2. `PHP Documentation` | `Looking into XSS attack prevention` | [PHP Manual]([https://stackoverflow.com/](https://www.php.net/htmlspecialchars))
3. `MDN Web Docs` | `PHP and HTML best practices` | [MDN PHP Guide](https://developer.mozilla.org/en-US/docs/Web/PHP)
4. `W3Schools` | `Loops, conditionals, functions` | [W3Schools PHP](https://www.w3schools.com/php/)
5. `Youtube Video` | `Basic PHP Overview` | [PHP Tutorial Series](https://www.youtube.com/watch?v=a7_WFUlFS94)
6. `Stack Overflow` | `Can you use HTML inside PHP echo?` | [Stack Overflow Thread](https://stackoverflow.com/questions/46918709/can-you-use-html-inside-php-echo)
7. `PHP Manual` | `Using inline styles within PHP echo statements` | [PHP Manual](https://www.php.net/manual/en/function.echo.php)
8. `MDN Web Docs` | `Best practices for integrating JavaScript with PHP` | [MDN Guide](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Fetching_data)
9. `PHP and JavaScript` | `Does JavaScript need to be in a separate file or can it be in PHP?` | [Stack Overflow Discussion](https://stackoverflow.com/questions/43502956/should-javascript-be-in-a-separate-file-or-included-in-php)
10. `CSS-Tricks` | `Proper ways to style PHP-generated HTML with inline CSS and external stylesheets` | [CSS-Tricks](https://css-tricks.com/)

## Estimated Hours
#### This week, I spent `6` hours learning PHP and related topics for this week's practical.

## Content Insights
> Guiding statements/questions: :bulb:
> - Entries should not be general. Instead, they must reveal insights about your specific learnings. I'd like to remind you that instead of listing what you have done, please remember what you have learnt while doing it.
> - Use complete sentences and record your insights so that you will understand them when you reread them in a few weeks. - Lindsay Ward
> - Sometimes there are not any real *'insights'*, just acknowledge this and don't make things up.

Building a PHP-driven site made me rethink how **backend logic meets frontend structure**. Initially, I struggled with **mixing PHP and HTML incorrectly**, which led to syntax errors. Fixing these reinforced that **keeping code modular** (using `include`) makes things cleaner and easier to maintain.

I also experimented with **capturing user input** using `$_POST` and learned how to **sanitise it** to prevent security issues; an insight I noted as a must-have in a secure production environment. Loops (`for`, `while`, `foreach`) helped **automate content**, which is vital for scalable web apps.

A fun insight was learning how to integrate **JavaScript with PHP** to dynamically fetch new content (random facts). I gained the insight that you can have languages talk through eachother, such as when you echo raw HTML/Javascript or even take it one step further and have an echo of raw HTML that contains and in-line style. Something like:
```php
<?php
echo "<h2 style='text-align: center;'>Home Page</h2>";
?>
```

## Career/Employability/Learning Insights
>**Career**: How can your learnings aid your career? <br>
>**Employability**: Are these skills transferable to the real world? <br>
>**Insights**: What have you learned about yourself from your insights? <br>
> - How does the industry use what I have learned today?
> - How do I see myself using the skills I have learned today for my career?
> - What careers use these skills, and are they something I am looking for or working towards?
> - Was there something specific about the way I learned things that was effective this week?

**Career Insights**: PHP is an extremely valuable skill to add to my coding career, it is in backend development everywhere with a particularly large spot being WordPress. This week reinforced my knowledge on PHP and how it is structured with and around HTML/CSS/Javascript. This provided me with great insight in the core and foundation knowledge behind the scenes; something critical in real-world projects. Learning how PHP and JavaScript work together also stood out as modern web apps rely on seamless backend-frontend communication, and understanding both sides makes me more versatile as a developer.

**Employability Insights**: Debugging PHP errors, structuring sites with include, and separating JavaScript from PHP weren’t just technical exercises, they showed me how clean and maintainable code makes collaboration easier. Companies don’t just want coders, they want developers who can write efficient, scalable applications that won’t become a nightmare to maintain.

**Personal Learning Insights**: PHP has taught me patience, small errors break everything, and debugging is often half the battle. However, I was quite impressed with the debugging log in my local environment and found it a useful tool to resolve errors. I also realised how backend logic and frontend interaction need to strike a balance where PHP does the heavy lifting of dynamic content while HTML does the standard static elements. This week has made me feel much more confident with PHP, which was previously a bit of a dark spot in my basic language knowledge.
---
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Original work of ***Casey Summers***
