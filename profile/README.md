![salome_logo_anim_big](https://github.com/SalomePlatform/.github-private/assets/52162083/cfd584d8-cc36-4156-8252-112dc9aadc82)
## What is SALOME, why use it ? ##

Numerical simulation in various industries relies on high-performance methods in fluid mechanics, structural mechanics, electromagnetism, and more. SALOME, an open-source platform, offers engineers, researchers, and practitioners a comprehensive solution with modules for CAD, meshing, coupling of phenomena, visualization, calculation supervision, uncertainties, and more. Users can easily access these modules through a user-friendly GUI or Python scripts to create customized domain-specific applications. SALOME's collaborative development approach and availability under the GNU LGPL ensure optimal use of computer resources, making it a go-to choice for organizations like EDF and CEA.

## Who is responsible for developing SALOME ? ##
SALOME, an open-source framework developed since the early 2000s, has grown through contributions from many individuals and partners. The collaborative efforts of these key partners have been instrumental in shaping SALOME into what it is today:

<p>
  <img width="60" src="https://github.com/SalomePlatform/.github-private/assets/52162083/f82b82a2-c27e-40ce-a439-34dd0430a3ee" alt="CEA Logo" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  CEA - French Alternative Energies and Atomic Energy Commission
</p>

<p>
  <img width="100" src="https://github.com/SalomePlatform/.github-private/assets/52162083/9edfe76e-a35b-4737-9b4c-85039c30ef79" alt="EDF Logo" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  EDF - Électricité de France
</p>

<p>
  <img width="100" src="https://github.com/SalomePlatform/.github-private/assets/52162083/773f978a-a1ca-4490-9d50-da377c8168ff" alt="OCC Logo" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  OCC - Open Cascade Technology
</p>


## Where can I find the latest SALOME documentation ? ##
- [User documentation page for SALOME](https://docs.salome-platform.org/latest/main/gui.html)
- [Developer documentation page for SALOME](https://docs.salome-platform.org/latest/main/tui.html)

## How to install SALOME ? 

- If you are looking to use SALOME, we provide precompiled binaries which simplifies the installation process. You can find these binaries [here](https://www.salome-platform.org/?page_id=2433)
- For developers who are looking to self install SALOME we highly recommend using [*SAT*](https://github.com/SalomePlatform/sat). Our [wiki](https://github.com/SalomePlatform/.github/wiki/) page explains more detailed procedure on self installation via *SAT*. One can also follow [Cmake](https://cmake.org/) based self installation procedure explained [here](https://docs.salome-platform.org/latest/dev/cmake/html/index.html)

## How do I contribute to SALOME on GitHub ? ##

As an external developer, we accept [pull-requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) for source code improvements or modifications specifically for the *main* branches of the relevant repository where you want to contribute. 

#### How do I, as an external developer, open a pull-request for my developments? ####

Let us take an example that you want to contribute to our *shaper* source code. So here is what you need to do 

- Fork the *shaper* repository from  your personal GitHub account. Learn how to fork [here](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
- Clone this forked repository to your local machine. Find instructions on how to clone a repository [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) 
- Make the necessary modifications to the source code files.
- After completing the changes (we highly recommend testing them locally),  [add -> commit -> push](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository) the changes to your forked *shaper* repository.
- Visit the *shaper* repository on [SalomePlatform](https://github.com/SalomePlatform) GitHub page and create a pull-request. Learn how to create a pull request [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork).
	- The pull request will trigger a series of CI tests to ensure SALOME compiles and remains stable.
	- A SALOME expert will be assigned as a [Reviewer](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/about-pull-request-reviews) for your pull request.
	- Expect communication with the reviewer regarding code edits, understanding the proposed changes, possible modifications, etc.
- The reviewer will handle the merging of your changes into the SALOME source code.

![](https://komarev.com/ghpvc/?username=SalomePlatform&style=for-the-badge&color=green&abbreviated=true)
