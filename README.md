<!--readme-for-root-start-->

<img alt="" width="500px" align="left" src="KubeStellar-with-Logo.png" />

<br/>
<br/>
<br/>
<br/>

## Multi-cluster Configuration Management for Edge, Multi-Cloud, and Hybrid Cloud

[![](https://img.shields.io/badge/first--timers--only-friendly-blue.svg?style=flat-square)](https://www.firsttimersonly.com/)&nbsp;&nbsp;&nbsp;
[![](https://github.com/kubestellar/kubestellar/actions/workflows/broken-links-crawler.yml/badge.svg)](https://github.com/kubestellar/kubestellar/actions/workflows/broken-links-crawler.yml)
[![](https://www.bestpractices.dev/projects/8266/badge)](https://www.bestpractices.dev/projects/8266)
[![](https://api.scorecard.dev/projects/github.com/kubestellar/kubestellar/badge)](https://scorecard.dev/viewer/?uri=github.com/kubestellar/kubestellar)
[![](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/kubestellar)](https://artifacthub.io/packages/search?repo=kubestellar)
<a href="https://kubernetes.slack.com/archives/C058SUSL5AA"> 
    <img alt="Join Slack" src="https://img.shields.io/badge/KubeStellar-Join%20Slack-blue?logo=slack">
  </a>

**KubeStellar** is a Cloud Native Computing Foundation (CNCF) Sandbox project that simplifies the deployment and configuration of applications across multiple Kubernetes clusters. It provides a seamless experience akin to using a single cluster, and it integrates with the tools you're already familiar with, eliminating the need to modify existing resources.

KubeStellar is particularly beneficial if you're currently deploying in a single cluster and are looking to expand to multiple clusters, or if you're already using multiple clusters and are seeking a more streamlined developer experience.


![KubeStellar High Level View](docs/content/images/kubestellar-high-level.png)


The use of multiple clusters offers several advantages, including:

- Separation of environments (e.g., development, testing, staging)
- Isolation of groups, teams, or departments
- Compliance with enterprise security or data governance requirements
- Enhanced resiliency, including across different clouds
- Improved resource availability
- Access to heterogeneous resources
- Capability to run applications on the edge, including in disconnected environments

In a single-cluster setup, developers typically access the cluster and deploy Kubernetes objects directly. Without KubeStellar, multiple clusters are usually deployed and configured individually, which can be time-consuming and complex.

KubeStellar simplifies this process by allowing developers to define a binding policy between clusters and Kubernetes objects. It then uses your regular single-cluster tooling to deploy and configure each cluster based on these binding policies, making multi-cluster operations as straightforward as managing a single cluster. This approach enhances productivity and efficiency, making KubeStellar a valuable tool in a multi-cluster Kubernetes environment.

## Website

For usage, architecture, and other documentation, see [the website](https://kubestellar.io).

## Contributing

We ❤️ our contributors! If you're interested in helping us out, please head over to our [Contributing](https://github.com/kubestellar/kubestellar/blob/main/CONTRIBUTING.md) guide and be sure to look at `main` or the release of interest to you.

This community has a [Code of Conduct](./CODE_OF_CONDUCT.md). Please make sure to follow it.

## Our Roadmap
Have a look at what we are working on next, see our [Roadmap](docs/content/direct/roadmap.md) 

## Getting in touch

There are several ways to communicate with us:

Instantly get access to our documents and meeting invites at http://kubestellar.io/joinus

- The [`#kubestellar-dev` channel](https://kubernetes.slack.com/archives/C058SUSL5AA) in the [Kubernetes Slack workspace](https://slack.k8s.io)
- Our mailing lists:
    - [kubestellar-dev](https://groups.google.com/g/kubestellar-dev) for development discussions
    - [kubestellar-users](https://groups.google.com/g/kubestellar-users) for discussions among users and potential users
- Subscribe to the [community calendar](https://calendar.google.com/calendar/event?action=TEMPLATE&tmeid=MWM4a2loZDZrOWwzZWQzZ29xanZwa3NuMWdfMjAyMzA1MThUMTQwMDAwWiBiM2Q2NWM5MmJlZDdhOTg4NGVmN2ZlOWUzZjZjOGZlZDE2ZjZmYjJmODExZjU3NTBmNTQ3NTY3YTVkZDU4ZmVkQGc&tmsrc=b3d65c92bed7a9884ef7fe9e3f6c8fed16f6fb2f811f5750f547567a5dd58fed%40group.calendar.google.com&scp=ALL) for community meetings and events
    - The [kubestellar-dev](https://groups.google.com/g/kubestellar-dev) mailing list is subscribed to this calendar
- See recordings of past KubeStellar community meetings on [YouTube](https://www.youtube.com/@kubestellar)
- See [upcoming](https://github.com/kubestellar/kubestellar/issues?q=is%3Aissue+is%3Aopen+label%3Acommunity-meeting) and [past](https://github.com/kubestellar/kubestellar/issues?q=is%3Aissue+is%3Aclosed+label%3Acommunity-meeting) community meeting agendas and notes
- Browse the [shared Google Drive](https://drive.google.com/drive/folders/1p68MwkX0sYdTvtup0DcnAEsnXElobFLS?usp=sharing) to share design docs, notes, etc.
    - Members of the [kubestellar-dev](https://groups.google.com/g/kubestellar-dev) mailing list can view this drive
- Follow us on:
   - LinkedIn - [#kubestellar](https://www.linkedin.com/feed/hashtag/?keywords=kubestellar)
   - Medium - [kubestellar.medium.com](https://medium.com/@kubestellar/list/predefined:e785a0675051:READING_LIST)


## ❤️ Contributors

Thanks go to these wonderful people:

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- readme: collaborators,contributors -start -->
<table>
	<tbody>
		<tr>
            <td align="center">
                <a href="https://github.com/clubanderson">
                    <img src="https://avatars.githubusercontent.com/u/407614?v=4" width="100;" alt="clubanderson"/>
                    <br />
                    <sub><b>Andy Anderson</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/MikeSpreitzer">
                    <img src="https://avatars.githubusercontent.com/u/14296719?v=4" width="100;" alt="MikeSpreitzer"/>
                    <br />
                    <sub><b>Mike Spreitzer</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/kcp-ci-bot">
                    <img src="https://avatars.githubusercontent.com/u/134318005?v=4" width="100;" alt="kcp-ci-bot"/>
                    <br />
                    <sub><b>kcp CI Bot</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/ezrasilvera">
                    <img src="https://avatars.githubusercontent.com/u/13567561?v=4" width="100;" alt="ezrasilvera"/>
                    <br />
                    <sub><b>Ezra Silvera</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/waltforme">
                    <img src="https://avatars.githubusercontent.com/u/8633434?v=4" width="100;" alt="waltforme"/>
                    <br />
                    <sub><b>Jun Duan</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/francostellari">
                    <img src="https://avatars.githubusercontent.com/u/50019234?v=4" width="100;" alt="francostellari"/>
                    <br />
                    <sub><b>Franco Stellari</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/openshift-merge-robot">
                    <img src="https://avatars.githubusercontent.com/u/30189218?v=4" width="100;" alt="openshift-merge-robot"/>
                    <br />
                    <sub><b>OpenShift Merge Robot</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/nirrozenbaum">
                    <img src="https://avatars.githubusercontent.com/u/19717747?v=4" width="100;" alt="nirrozenbaum"/>
                    <br />
                    <sub><b>Nir Rozenbaum</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/vMaroon">
                    <img src="https://avatars.githubusercontent.com/u/73340153?v=4" width="100;" alt="vMaroon"/>
                    <br />
                    <sub><b>Maroon Ayoub</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/yana1205">
                    <img src="https://avatars.githubusercontent.com/u/113283236?v=4" width="100;" alt="yana1205"/>
                    <br />
                    <sub><b>Takumi Yanagawa</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/andreyod">
                    <img src="https://avatars.githubusercontent.com/u/16204273?v=4" width="100;" alt="andreyod"/>
                    <br />
                    <sub><b>Andrey Odarenko</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/pdettori">
                    <img src="https://avatars.githubusercontent.com/u/6678093?v=4" width="100;" alt="pdettori"/>
                    <br />
                    <sub><b>Paolo Dettori</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/effi-ofer">
                    <img src="https://avatars.githubusercontent.com/u/18140413?v=4" width="100;" alt="effi-ofer"/>
                    <br />
                    <sub><b>Effi Ofer</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/KPRoche">
                    <img src="https://avatars.githubusercontent.com/u/25445603?v=4" width="100;" alt="KPRoche"/>
                    <br />
                    <sub><b>Kevin Roche</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/fileppb">
                    <img src="https://avatars.githubusercontent.com/u/124100147?v=4" width="100;" alt="fileppb"/>
                    <br />
                    <sub><b>fileppb</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/dumb0002">
                    <img src="https://avatars.githubusercontent.com/u/25727844?v=4" width="100;" alt="dumb0002"/>
                    <br />
                    <sub><b>Braulio Dumba</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/namasl">
                    <img src="https://avatars.githubusercontent.com/u/144150872?v=4" width="100;" alt="namasl"/>
                    <br />
                    <sub><b>Nick Masluk</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/amanroa">
                    <img src="https://avatars.githubusercontent.com/u/26678552?v=4" width="100;" alt="amanroa"/>
                    <br />
                    <sub><b>Aashni Manroa</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/pratik-mahalle">
                    <img src="https://avatars.githubusercontent.com/u/124587957?v=4" width="100;" alt="pratik-mahalle"/>
                    <br />
                    <sub><b>Pratik Mahalle</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/JonathanWentaoBao">
                    <img src="https://avatars.githubusercontent.com/u/171893847?v=4" width="100;" alt="JonathanWentaoBao"/>
                    <br />
                    <sub><b>JonathanWentaoBao</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/jaydee029">
                    <img src="https://avatars.githubusercontent.com/u/92215138?v=4" width="100;" alt="jaydee029"/>
                    <br />
                    <sub><b>Dhruv Jain</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/katamyra">
                    <img src="https://avatars.githubusercontent.com/u/45225228?v=4" width="100;" alt="katamyra"/>
                    <br />
                    <sub><b>Krish Katariya</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Shruti78">
                    <img src="https://avatars.githubusercontent.com/u/104200088?v=4" width="100;" alt="Shruti78"/>
                    <br />
                    <sub><b>Shruti Murthy</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/manzil-infinity180">
                    <img src="https://avatars.githubusercontent.com/u/119070053?v=4" width="100;" alt="manzil-infinity180"/>
                    <br />
                    <sub><b>Rahul Vishwakarma</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/Mohiit70">
                    <img src="https://avatars.githubusercontent.com/u/120316966?v=4" width="100;" alt="Mohiit70"/>
                    <br />
                    <sub><b>Mohit Bisht</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/grahamwhiteuk">
                    <img src="https://avatars.githubusercontent.com/u/1632332?v=4" width="100;" alt="grahamwhiteuk"/>
                    <br />
                    <sub><b>Graham White</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/aishwarya-mathew">
                    <img src="https://avatars.githubusercontent.com/u/46677213?v=4" width="100;" alt="aishwarya-mathew"/>
                    <br />
                    <sub><b>Aishwarya </b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/aslom">
                    <img src="https://avatars.githubusercontent.com/u/1648338?v=4" width="100;" alt="aslom"/>
                    <br />
                    <sub><b>Aleksander Slominski</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/benzha14">
                    <img src="https://avatars.githubusercontent.com/u/93015397?v=4" width="100;" alt="benzha14"/>
                    <br />
                    <sub><b>Benson Zhang</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/xrstf">
                    <img src="https://avatars.githubusercontent.com/u/127499?v=4" width="100;" alt="xrstf"/>
                    <br />
                    <sub><b>Christoph Mewes</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/RealRTorres">
                    <img src="https://avatars.githubusercontent.com/u/72537940?v=4" width="100;" alt="RealRTorres"/>
                    <br />
                    <sub><b>RealRTorres</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/yuji-watanabe-jp">
                    <img src="https://avatars.githubusercontent.com/u/26372857?v=4" width="100;" alt="yuji-watanabe-jp"/>
                    <br />
                    <sub><b>Yuji Watanabe</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/rchen-devv">
                    <img src="https://avatars.githubusercontent.com/u/169481903?v=4" width="100;" alt="rchen-devv"/>
                    <br />
                    <sub><b>rchen-devv</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/msteinder">
                    <img src="https://avatars.githubusercontent.com/u/9352004?v=4" width="100;" alt="msteinder"/>
                    <br />
                    <sub><b>msteinder</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/fab7">
                    <img src="https://avatars.githubusercontent.com/u/15231306?v=4" width="100;" alt="fab7"/>
                    <br />
                    <sub><b>Francois Abel</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/tingdai">
                    <img src="https://avatars.githubusercontent.com/u/9260276?v=4" width="100;" alt="tingdai"/>
                    <br />
                    <sub><b>Ting Dai</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/jewzaam">
                    <img src="https://avatars.githubusercontent.com/u/480388?v=4" width="100;" alt="jewzaam"/>
                    <br />
                    <sub><b>Naveen Malik</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/mra-ruiz">
                    <img src="https://avatars.githubusercontent.com/u/16118462?v=4" width="100;" alt="mra-ruiz"/>
                    <br />
                    <sub><b>Maria Camila Ruiz Cardenas </b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/qrkourier">
                    <img src="https://avatars.githubusercontent.com/u/1434400?v=4" width="100;" alt="qrkourier"/>
                    <br />
                    <sub><b>Kenneth Bingham</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/jelmersnoeck">
                    <img src="https://avatars.githubusercontent.com/u/815655?v=4" width="100;" alt="jelmersnoeck"/>
                    <br />
                    <sub><b>Jelmer Snoeck</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/rubambiza">
                    <img src="https://avatars.githubusercontent.com/u/11816517?v=4" width="100;" alt="rubambiza"/>
                    <br />
                    <sub><b>Gloire Rubambiza </b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/eaepstein">
                    <img src="https://avatars.githubusercontent.com/u/56738503?v=4" width="100;" alt="eaepstein"/>
                    <br />
                    <sub><b>eaepstein</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/cmadam">
                    <img src="https://avatars.githubusercontent.com/u/19595758?v=4" width="100;" alt="cmadam"/>
                    <br />
                    <sub><b>Constantin M. Adam</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/ncdc">
                    <img src="https://avatars.githubusercontent.com/u/354?v=4" width="100;" alt="ncdc"/>
                    <br />
                    <sub><b>Andy Goldstein</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/thinkahead">
                    <img src="https://avatars.githubusercontent.com/u/7507482?v=4" width="100;" alt="thinkahead"/>
                    <br />
                    <sub><b>Alexei Karve</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/algoritmoalex">
                    <img src="https://avatars.githubusercontent.com/u/9136079?v=4" width="100;" alt="algoritmoalex"/>
                    <br />
                    <sub><b>Alex Rivera</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Harmedox">
                    <img src="https://avatars.githubusercontent.com/u/23058620?v=4" width="100;" alt="Harmedox"/>
                    <br />
                    <sub><b>Abdulhamid Adebayo</b></sub>
                </a>
            </td>
		</tr>
	<tbody>
</table>
<!-- readme: collaborators,contributors -end -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<br>
<br>

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fkubestellar%2Fkubestellar.svg?type=large&issueType=license)](https://app.fossa.com/projects/git%2Bgithub.com%2Fkubestellar%2Fkubestellar?ref=badge_large&issueType=license)
<br>
<br>

<td>
    <a href="https://landscape.cncf.io">
        <img src="/docs/overrides/images/cncf-color.png" width="300px;" alt="Cloud Native Computing Foundation Logo"/>
    </a>
</td>
<br>We are a Cloud Native Computing Foundation sandbox project.
<br>Kubernetes and the Kubernetes logo are registered trademarks of The Linux Foundation® (TLF).
<br>The Linux Foundation has registered trademarks and uses trademarks. For a list of trademarks of The Linux Foundation, please see our <a href="https://www.linuxfoundation.org/legal/trademark-usage">Trademark Usage page</a>.
<br>© 2022-2024. The KubeStellar Authors.
<!--readme-for-root-end-->
