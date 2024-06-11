
# YAML for resume ATS sharing, Why NOT, Is there something better ?


Acronyms, yes the first time that we face of with one acronym we need to google it.

What means ATS: Applicant Tracking System, nowadays talent hiring company need to process
many candidates as possible and to do that uses software that read resumes writen in pdf, doc or html files.

But this formats were designed with the aim of presenting data, they have a lot of information about
fonts type, font size, colors, margins, positions, etc.. and are not well designed for storing data,
therefore are difficult to parse and extract information from them.

Many times we are facing with the button [Import you resume here], but after doing it we can saw
how the system fail to import relevant topics. 

Then we search the web for "How to write an ATS-friendly resume" and found a lot of 
opinionated recipes, but we need a infallible "Canonical" way.

The need of standarization appear.

So we need a human legible format, we need to separate data from presentation,
we need an agnostic way to share our resumes.

## What means YAML ?

Basically YAML is markup language, ....(you can google it if need more info).

Why choose yaml, because between all human legible format (txt, csv, xml, json)
we have that some are flat (txt), and have lack of hierarchy (csv), some are verbose (xml), some are complicated for non programmers (json), 
and some are only for presentation (md).

YAML files does not have strange symbols, in a first glance is similar to a book index, 
all academic people are familiar with a book index, and is widely used in cloud environments.

We can write a yaml file with any standard txt editor, does not need to buy any specific software, all the computers and phones has one installed, also yaml files are easy to validate, search "yaml online validator" and is easy to parse.


The more important thing for a programmer point of view, is that there are sotfware libraries for parsing in every computer language,
thus is easy to write import and export programs.

Until now sound good but how to start ??

Implement a new standard its'nt so easy, There are some things that we can start doing:

First write your resume:

```YourCamelCaseName_role.ats.yml```

Something like that:

```HomerJSimpson_NuclearPlantOperator.ats.yml```

Validate it, by example in: [YAML validator](https://www.yamllint.com/)

Store it somewhere places that has visibility: your GitHub account, your personal Blog.

After this, many companies will become aware of this behavior and will begin to develop other forms of data ingestion.

Also here is where big players company like Linkedin play an important role.

They must implement a feature that let us import and export our resumes in YAML format.
And also implement an ATS, api endpoint to share our resume with others:

```www.linkedin.com/ats/HomerJSimpson```

I know that not sound easy, but someone has to start, and some day it would be a standard.

Then recruiting-software companies Icims, Taleo, Jobvite, SmartRecruit, Bullhorn, etc...
will follow the initiative.

Let's see an example resume in yaml, to improve the likelihood of a widespread adoption I wrote a short version of the Elon Musk resume.

[Elon Musk yaml resume](./ElonMusk_Technoking.ats.yml)

Please share and adopt it.



