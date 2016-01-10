# Review of Chef Essentials Class

## Introduction

This document serves as my scratch pad for feedback. It is work in progress and I'll try to update it regularly.

## First Pass of General Feedback

- The idea of starting from the super simple use cases is nice

- introducing git in this very basic training is confusing

- Weird that we have a cookbook and we're still using `chef-apply`

- Testing is performed too early. And without real context

- At one point we ran `kitchen test` but we didn't update the tests to cover the updated recipe – why?

- Running `kitchen test` so often slows things down and make chef come across as not the tool to quickly develop a POC.

- We use `kitchen` but we're not using the TDD lifecycle – "write tests -> test breaks -> write code -> test passes"

- Do students now need email access in class to sign up for an account on manage.chef.io? That could be a blocker!

- Why `berks` so early and not `knife cookbook upload`, at least initially.  Gets people using a workflow that might not suit them.

- I did have proxy issues with `berks`

- We set a run list, but we haven't discussed what a run list is yet.

- Why are we introducing the concept of library cookbooks in community cookbooks section.  Advanced topic?
