## Table of Contents

- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)

  - [Headings](#headings)

  - [Text Formatting](#text-formatting)
 
  - ## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  

This ensures your notes are easy for you (and others) to read later.

---

## Headings

**When to use:** Organize your notebook into sections (like days, topics, or projects).  

- `#` for the notebook title (use once at the top).  

- `##` for each day or major topic.  

- `###` for subsections (like "Notes", "Practice", "Reflections").  

# Example:

# My Coding Notebook

## Day 1

### Notes

### Practice

# Text Formatting

When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

# Example:

**Class** = a blueprint for objects  

*Remember:* always test your code  

Use `System.out.println()` to print

 

# Code Blocks

When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

# Example:

```java

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello World!");

    }

}

```

# Lists

When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

# Example:

Define the class
Write the main method
Test your program
Variables

- Loops

- Conditionals

 

# Checklists

When to use: Track progress on assignments or tasks.

# Example:

[x] Complete coding warm-up

- [ ] Finish project draft

- [ ] Reflect on learning

 

# Blockquotes

When to use: Call out notes, reminders, or teacher comments.

# Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

# Tables

When to use: Compare values, track progress, or organize data neatly.

# Example:

| Task        | Status   | Notes          |

|--------------|------------|-----------------| 

| Homework 1  | Done #  | Submitted      |

| Homework 2  | Pending  | Needs review   |

 

# Links & Images

When to use: Add references, resources, or visuals.

# Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

To make an image that is a link, paste the image, then add the following before it, replacing website address with the link:

<a href="website address">

And after the image info, add: </a>

# Collapsible Sections

When to use: Hide solutions, extended notes, or extra details.

# Example:

<details>

  <summary>Click to reveal solution</summary>

  

System.out.println("Answer: 42");

</details>

 

# Footnotes

When to use: Add references or side notes without cluttering the page.

# Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

# Style Rules

Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

# Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.

# Vocabulary
console:	The area of a computer that notes from a program can be printed to. Kind of like a notebook.	
On Skill Struck (python, javascript, and java) this is the area that your code is printed to.

Java comments	Information in you program that does not run, but simply meant to be informative.	
//This is a comment in Java

internal link	A link that takes a user to a different page in the same site.	
The following link will take users to the hobbies page within the site.
<a href=“hobbies.html”>Take me to my Hobbies page</a

incrementor: it is '++' where it will increase your number by 1.
decrementor: it is '--" where it will decrease your number by 1.


• pool is an ArrayList, which acts like a dynamic, expanding container used to store multiple items in order.
• new Question(...) creates a individual question object containing text (like "Does Neptune have a greater mass than earth?") and its correct boolean answer (true or false).
• .add() is the built-in Java method that takes that newly created question and safely places it inside the container.
By calling pool.add(...) twenty times, the code builds a collection (or "pool") of 20 different trivia questions that can later be randomized, looped through, or used in a quiz game.


Think of a regular array like a grid of lockers built into a wall—if you buy 5 lockers, you can only ever store 5 items. If you get a 6th item, you have to buy a whole new set of lockers.
An ArrayList is like a backpack. If you drop another item inside, it stretches to fit it.

Why use an ArrayList?

• Dynamic Resizing: You don't need to know how many questions you have ahead of time. You can keep calling .add() forever.
• Built-in Tools: It comes with pre-made helper functions to easily manipulate your data:
	• pool.add(item) – Puts an item at the end.
	• pool.remove(0) – Removes the very first item.
	• pool.size() – Tells you exactly how many items are currently inside.
	• pool.get(2) – Grabs the third item in the list (since counting starts at 0).
• Maintains Order: It remembers exactly what order you added your items in.


Instead of forcing you to write everything from scratch, Java lets you "import" these tools so you can use them instantly in your program.
Here is exactly what each specific tool does for your quiz game:
• import java.util.ArrayList;
Loads the dynamic, expandable list container you used to hold your Question objects.
• import java.util.Collections;
Provides utility tricks for collections. In a quiz game, this is usually imported specifically to use Collections.shuffle(pool);, which randomly mixes up your questions so they aren't in the same order every game.
• import java.util.List;
Loads the general rules (interface) for lists. It allows you to write clean code like List<Question> pool = new ArrayList<>();.
• import java.util.Scanner;
Loads the tool that reads user input. This is what lets your program pause, wait for the player to type their answer (like "true" or "false") into the console, and press Enter.

external documentation	External documentation is the information about your code that's kept outside the actual source files, like user guides, API references, or manuals, to help others understand how to use or work with your program.	

Concatenation is a very long word which means to combine two strings together with a + sign.
