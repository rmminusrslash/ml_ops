# Machine Learning Operations


## Building
I use poetry. It has several advantages over pip and conda, some important ones:
- You can specify the python version 
- You get a reproducable environment because it pins transitive dependencies and writes them to a poetry.lock file
- It supports uninstalling all libraries not listed in the current poetry.lock file

## Development Libraries
- this is actually before doing any ops. But the library is so useful, I have to throw it in for model/data testing during development: https://deepchecks.com/


## Reading

### Introductionary Material


### Expert Reading

Here are some of my favourite resources:

#### What’s your ML test score? A rubric for ML production systems
Eric Breck Shanqing Cai Eric Nielsen Michael Salib D. Sculley
Reliable Machine Learning in the Wild - NIPS 2016 Workshop (2016)

Abstract
Using machine learning in real-world production systems is complicated by a host of issues not found in small toy examples or even large offline research experiments. Testing and monitoring are key considerations for assessing the production-readiness of an ML system. But how much testing and monitoring is enough? We present an ML Test Score rubric based on a set of actionable tests to help quantify these issues.

https://research.google/pubs/pub45742/


