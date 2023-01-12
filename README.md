<header>
<p align="center">
    <img src=".github/images/geoid-logo_light.png" width="20%" height="20%" alt="Geoid Logo">
</p>
<p align='center' style='border-bottom: none;'><b>Geoid</b></p>
<h1 align='center' style='border-bottom: none;'> GSP</h1>
<h3 align='center'>Geoid Standards Proposals</h3>
</header>


<br/>
<details open="open">
<summary>Table of Contents</summary>

- [About](#about)
- [Process](#process)
- [Contributing](#contributing)
- [Help](#help)

</details>


## About

A Geoid Standards Proposal (GSP) describes standards for the Geoid ecosystem. The Geoid Standards Proposal GitHub is a community-based initiative.  
GSP process is not supposed to be a substitute for Geoid Governance process and is meant to focus only on commonly agreed usage patterns rather than protocol adjustments.  

<!-- > __Disclaimer__: The Geoid network is relatively young and many ecosystem
projects are just getting started. While the interoperability aspect of
Geoid, parachains and community tools are still being actively developed,
participants of the ecosystem can create proposals for certain mechanisms for
the wider community to use. As of now, we loosely accept proposals that we might
not actively endorse, do not expect to be implemented or might fall outside the
scope of the GSP. We think many standards will be adopted organically (with some
coordination) and change with time. We expect that a more firm process for
standardization will evolve as adoption takes place. Certain proposals might be
modified, replaced or deprecated. -->

---



## Process  

Below is the workflow of a successful GSP:
```
1. Draft -> 2. Call for Feedback -> 3. Published -> 4. Integrated
```
1. **Draft:** A valid draft, which is merged into into the [draft
   subfolder](./GSPs/drafts) and actively improved together with the community.
2. **Call for Feedback:** The GSP will be shared on different channels for
   additional feedback for at least 2 weeks. The result of this step is either
   an acceptance of the standard (->Published) or the rejection (->Draft).
3. **Published:** Any further changes are unlikely, and developers can start
   integrating the GSP.
4. **Integrated:** The GSP is actively used and a reference implementation
   exists.

In order to be **merged or accepted** for the different stages, reviewers need to approve a PR. Reviewers should be known experts in the topic covered by the GSP. 


## Contributing

Before you start writing a formal GSP, you should discuss an idea in the various community channels (see the [Geoid  website](https://geoid.org/)). A GSP should provide the motivation as well as a technical specification for the feature. 

1. Fork this repository.
2. In the newly created fork, create a copy of the template.
3. Fill out the [template](./src/gsp-template.md) with the details of your GSP. If your GSP requires images, the images should be integrated in a subdirectory of the src folder, which has your GSP number as the name.
4. Once you have completed the application, click on "create new pull request".
5. Rename the file with "psp-number_of_your_pr.md".
6. Update the pull request. 


## Help

* [GitHub Discussions](https://github.com/geoid-org/geoid-standard-proposals/discussions)
