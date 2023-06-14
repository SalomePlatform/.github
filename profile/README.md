![salome_logo_anim_big](https://github.com/SalomePlatform/.github-private/assets/52162083/cfd584d8-cc36-4156-8252-112dc9aadc82)
## What is SALOME, why use it ? ##

Numerical simulation in various industries relies on high-performance methods in fluid mechanics, structural mechanics, electromagnetism, and more. SALOME, an open-source platform, offers engineers, researchers, and practitioners a comprehensive solution with modules for CAD, meshing, coupling of phenomena, visualization, calculation supervision, uncertainties, and more. Users can easily access these modules through a user-friendly GUI or Python scripts to create customized domain-specific applications. SALOME's collaborative development approach and availability under the GNU LGPL ensure optimal use of computer resources, making it a go-to choice for organizations like EDF and CEA. With over 150,000 downloads in 2021 alone, SALOME is recognized globally as an essential tool for engineering and research, fostering knowledge sharing and expertise to serve its diverse user base.

## Who is responsible for developing SALOME ? ##
SALOME, an open-source framework that has been under development since the early 2000s, boasts an extensive list of individuals and partners who have contributed to its evolution. The collaborative efforts of these key partners have been instrumental in shaping SALOME into what it is today:
- <img width="60" src="https://github.com/SalomePlatform/.github-private/assets/52162083/f82b82a2-c27e-40ce-a439-34dd0430a3ee" />  $~~~~~~~~~~~$ CEA - French Alternative Energies and Atomic Energy Commission

- <img width="100" src="https://github.com/SalomePlatform/.github-private/assets/52162083/9edfe76e-a35b-4737-9b4c-85039c30ef79" /> $~~$ EDF - Électricité de France 

- <img width="100" src="https://github.com/SalomePlatform/.github-private/assets/52162083/773f978a-a1ca-4490-9d50-da377c8168ff" /> $~~$ OCC - Open Cascade Technology

## Where can I find SALOME documentation ? ##
- [User documenatation page for SALOME 9.10](https://docs.salome-platform.org/latest/main/gui.html)
- [Developer documenatation page for SALOME 9.10](https://docs.salome-platform.org/latest/main/tui.html)



## How do I contribute to SALOME on GitHub ? ##

Our policy requires new developments to be made in the *develop* branches of SalomePlatform repositories. The *main* branches remain stable at the previous release. As an external developer, we accept [pull-requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) for source code improvements or modifications specifically for the develop branches of the relevant repository where you want to contribute. 

#### How do I, as an external devleloper, open a pull-request for my developments? ####

Let us take an example that you wants to contibute to our *shaper* source code. So here is what you need to do 

- Fork the *shaper* repository from to your personal GitHub account. Learn how to fork [here](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
- Clone this forked repository to your local machine. Find instructions on how to clone a repository [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) 
- Switch to the *devel* branch using the command `git checkout -b devel`
- Make the necessary modifications to the source code files.
- After completing the changes (we highly recommend testing them locally),  [add -> commit -> push](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository) the changes to your forked *shaper* repository.
- Visit the *shaper* repository on [SalomePlatform](https://github.com/SalomePlatform) GitHub page and create a pull-request - Learn how to create a pull request [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork).
	- The pull request will trigger a series of CI tests to ensure SALOME compiles and remains stable.
	- A SALOME expert will be assigned as a [Reviewer](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/about-pull-request-reviews) for your pull request.
	- Expect communication with the reviewer regarding code edits, understanding the proposed changes, possible modifications, etc.
- The reviewer will handle the merging of your changes into the SALOME source code.
	
	

## How to Cite SALOME ? ##

#### BibTeX ####
```
@misc{SALOME,
	title = {{SALOME: the open-source numerical platform for numerical simulation}},
	howpublished = {\url{https://www.salome-platform.org}},
	note = {Accessed: 2023}
}
``` 
#### APA ####
```
SALOME: the open-source numerical platform for numerical simulation. (2023). https://www.salome-platform.org
```
#### MLA ####
```
"SALOME: the open-source numerical platform for numerical simulation." (2023). https://www.salome-platform.org
```
#### ISO 690 ####
```
SALOME: the open-source numerical platform for numerical simulation, 2023, https://www.salome-platform.org
```


