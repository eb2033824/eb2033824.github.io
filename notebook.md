## Table of Contents

- [Blocks](#blocks)
- [Concepts](#concepts)
- [Vocabulary](#vocabulary)
- [Blocks](#blocks)
- [Concepts](#concepts)
- [Vocabulary](#vocabulary)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)
- [Headings](#headings)
  - [Text Formatting](#text-formatting)

## Blocks
Hat blocks are special event-handling block with a curved or flat top that starts a stack of code 
A Stack Block is a rectangular puzzle-piece command that performs a main action like moving a robot or setting a pen color
 C-Block is a control-flow block shaped like the letter "C" that wraps around other command blocks to repeat them or run them conditionally
 A Reporter block is oval-shaped block that reports a numeric or text value
 A Boolean/hexagonal block reports a condition as either true or false
 The Repeat block is an orange C-shaped control block that loops a set of commands a specific number of times
 The Wait until block pauses the program flow until a specific rule becomes true
an If Then block is a C-shaped control block that makes decisions based on a specific condition
The Forever block is a control structure that loops any code placed inside it indefinitely
## Concepts
Sequence- The specific order in which instructions are executed.

Parameters- The inputs given to a command to customize its behavior.

Loops / Iteration- Structures that repeat a block of code multiple times.

Sensors- Distance Sensor, Bumper Switch, and Optical Sensor allow the robot to detect walls, physical impacts, and object colors.

Booleans & Conditions-  expressions that evaluate to TRUE or FALSE

Sense → Think → Act- The continuous loop of a robot

Comparisons-  operations that compare two values to determine if a condition is TRUE or FALSE.

Coordinates- The X and Y values used to describe the exact position of a robot

Conditionals- Statements that allow a program to make decisions and execute different code

Patterns- Recognizing repeated behaviors or problems to create more algorithms
## Vocabulary
VR Robot + Playground- The virtual robot in VEXcode VR. It comes pre-built with pre-configured features like a drivetrain, pen, and multiple built-in sensors

Programming Language + Project- The interactive virtual grid workspace or 3D window where the VR Robot executes commands, maneuvers, and solves challenges

Behavior + Command- The physical action or response displayed by the VR Robot as a result of running a specific command or sequence of blocks

Drivetrain- Drivetrain blocks handle forward/backward movement, turning, and speed adjustments.

Loop + Iteration- A structural programming format a C-block used to repeat a segment of code either infinitely or a set number of times, reducing block redundancy.

Sensor + Bumper Sensor- Sensor is a hardware component built into the VR Robot that reads external real-time data from its current Playground, sending that data back to the program to drive decisions. Bumper sensor is a physical contact switch located on the front left and right sides of the robot. It outputs TRUE when physically pressed against a wall or obstacle, and FALSE when released.

Boolean + Condition + TRUE/FALSE- Boolean a primitive data format that can only hold one of two specific states: TRUE or FALSE. Condition a variable state or logical comparison expression like checking if a sensor is pressed that returns a Boolean value to control scripts. TRUE: The logic state confirming that a condition's requirements have been met.FALSE: The logic state confirming that a condition's requirements have not been met.

Distance Sensor + Threshold- 

Coordinate Plane + X/Y Coordinates- 

Location Sensor-

Comment	Comment

Eye Sensor-

Conditional Statement-




























  ## Markdown Style Guide for Coding Notebooks

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
