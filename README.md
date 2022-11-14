
| Date              |          |
|:------------------|:---------|
| 14 November 2022 | Assigned |
| Various          | Due      |
| Status            | [![GatorGrader](../../actions/workflows/main.yml/badge.svg)](../../actions/workflows/main.yml) |

# 

**Reported by `Official Mayor-Endorsed News` on `14 November 2022`**


## Overview

At this point, the world--to somewhat controlled extent--is yours. The task for the remainder of your time in `term-world` is a grand improvement, one that synthesizes everything you've gained over the course of the semester. This is an open-ended task that can be completed individually or in "partnerships" (groups which can span neighborhoods). While there are rules to this task, they are fewer than a traditional assignment, though the work is much larger.

### Supporting media

The following links to a playlist which features all videos from the semester.

[![YouTube thumbnail](http://img.youtube.com/vi/gGl5pvFqQr4/hqdefault.jpg)](https://www.youtube.com/channel/UCEoAhDAnKTvsaJ-f-OlyLcg/playlists?view=50&sort=dd&shelf_id=2)

For folks who need reference materials for subjects that weren't covered as part of coursework, but are integral to completion of the project, we maintain a [`project-demos` repository on GitHub](https://github.com/allegheny-college-cmpsc-100-fall-2022/project-demos). As others ask for demonstrations of given concepts, more will be added to this resource. There are already some examples there.

## Accessing `project` Content

In order to complete the workload for the `project` you'll first need to `clone` the `project` repository into your `workshop`.

When you `clone` a repository you're duplicating its contents and adding them to your local workspace. Since you'll be working collaboratively with your neighbors, you'll each need your own copy of the `project` to work with.

In order to keep some of the magic (read: somewhat convoluted code) that makes `term-world` work the way it does, **you are required to clone all additional repositories within the `workshop`, located within your `garage`.**

Head to GitHub and:
* click on the green `Code` button
* ensure that `SSH` is selected
* copy the link that appears in the window below

It might look something like `git@github.com:term-world/woodpile-dluman`.

Once you've copied this link, navigate to your terminal window and ensure you're still in the appropriate place (in this case, the topmost level of your `workshop`). Then, enter the command:

```
git clone COPIED-LINK-HERE
```

Be sure to replace the fragment `COPIED-LINK-HERE` with the link you copied. In the example regarding `woodpile-dluman`, the full command would look like:

```
git clone git@github.com:term-world/project-dluman
```

While `pull` is used to *update* the contents of a repository that already exists in your local workspace, `clone` is used to *replicate* the contents of a repository from GitHub and copy them to your local workspace.

## Completing `project` content

### Partnerships

Partnerships (i.e. self-selected groups) cannot be larger than `3` citizens. There will be no accommodations to this rule.

### Choosing a project

World projects are necessarily open. This means that you're able to select anything to work on, though the project will need to be of sufficient complexity and depth to warrant needing 3+ weeks for completion. The only area out-right forbidden in `term-world`: games. We need not of trifles, amusements, or diversions. We are building a world, after all.

#### Examples

Scale and scope (i.e. how much work and how much is affected by that work) will vary from project to project. As long as the difficulty and duration are appropriate to the individual(s) completing the work, this is not a factor in evaluation. No one gets "more points" by doing something harder, though all of yoru projects will challenge you.

For your consideration, the Office of the Mayor provides the following short list of potential projects, some of which may already be spoken for:

* a community power grid
* a world wallet system
* a world economy
* improvements to the inventory system
* proper vending machines
* citizen transportation

These examples do not contemplate the entire range of possibilities. There are many more for you to discover. Only one project can address a given specific area. The Mayor will collect projects that citizens suggest and approve them on a case-by-case basis.

### Work

There are various dates for documentation, demonstration, and final submission. Refer to the table below for these dates which are _hard deadlines_. Unless truly extenuating circumstances exist, these dates cannot be abridged.

|Work due              |Date                  |
|:---------------------|:---------------------|
|Proposal              |21 November 2022      |
|Progress Report       |2 December 2022       |
|Project Demonstration          |9 December 2022       |
|Final Report          |12:00p, 20 December 2022 |
|Final Project Code    |12:00p, 20 December 2022 |

### Proposal

This project starts by writing a clear proposal of the work you expect to complete over the course of this extended project. This work must be completed in the `docs/proposal.md` file. Here, you will be expected to outline:

* the members of your partnership
* the overall concept/statement of work for the project
* a pitch for the world value of the project (i.e. why is it worth doing?)
* a breakdown of the tasks associated with the project as you perceive them now
* an assessment of the scale and schedule for the work of the project

This is similar to how you've proposed various improvements over the course of the semester, though somewhat extended. For example, this proposal has many more dimensions than a traditional improvement and, thus, has a larger expected word count (`500 words`). 

### Progress Report

As the project develops, the Office of the Mayor expects progress. You will provide a `Progress Report` of no fewer than `500 words` which responds to questions in the `docs/progress.md` file. This will be accompanied by a demonstration 1 week later which should confirm or exceed expectations set by the writing in this document.

### Project Demonstration

By the date provided above, partnerships must provide a demonstration of their work. This demonstration must achieve the following:

* a brief (3 minute) non-technical walkthrough presentation of how the project works
* a short (5 minute) technical demonstration of the project
* a necessarily long question and answer session with Mayoral representatives

### Final Report

At the close of the work, each partnership must complete the `docs/report.md` file. This writing is an extended overview of the final specifications and instructions for the project. It must detail both the work completed and _how to use_ the projects that result. This report requires a minimum of `750 words`.

### Final Project Code

Final project code has one Golden Rule and many supporting rules of lesser metallic lustre. Not to bury the lede, the Golden Rule:

> The project code must run and achieve its intended task.

Of course, supporting this, the code must:

* Be coordinated using a `main.py` file in the `src` directory
* Use at least `3` self-written `module` files `import`ed across the range of included code
  * i.e. they don't have to all be in the `main.py`
* Use at least `1` `module` that we haven't studied at all this semester
  * you may need to install a package to use it; consult with course administrative staff to complete
  * there are already many on the server(s)
* Use at least one of each data structure:
  * `dictionary`
  * `list`
* Use at least 5 `function`s across the range of code provided

The above is not an exhaustive list of what code should contain in order to complete its job. In fact, it's highly unlikely that the above will be _all you need_.

## Submitting `project` Content

Considering that the work you're doing for the `project` is individual, there's no need to branch your work. However, getting in the habit of doing so is a _good habit_.

When you're ready to push to GitHub, do the normal `add` and `commit` routines. Recall:

```
git add NAME_OF_FILE_OR_DIRECTORY_TO_ADD
```

You may need to do this for either:

* Individual files (i.e. `git add Thingamajig.py`)
* Directories (i.e. `git add Thingamajig`)

```
git commit -m "Descriptive commit message"
```

### Pushing to a branch

Because you're branching--when it comes to push, run this slightly expanded command:

```
git push origin YOUR_BRANCH_NAME
```

We're still using `git push`, but this time we're adding an extra layer of information to the command; to be precise, we're specifically instructing `git` to push our changes to a particular branch of the repository (*your* branch). In the example regarding the `gadgets` department, the command to run would look like:

```
git push origin gadgets
```