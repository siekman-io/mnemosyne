<!--
####################################################
# ANSIBLE-PLAYBOOK README.md
#####################################################
#        _      _                            _
#    ___(_) ___| | ___ __ ___   __ _ _ __   (_) ___
#   / __| |/ _ \ |/ / '_ ` _ \ / _` | '_ \  | |/ _ \
#   \__ \ |  __/   <| | | | | | (_| | | | |_| | (_) |
#   |___/_|\___|_|\_\_| |_| |_|\__,_|_| |_(_)_|\___/                 
#
#              Created by Jouke Siekman
#             Netherlands 2023 Leerbroek
#                https://siekman.io
#
#####################################################
## README.MD {{playbook_name}}
#####################################################
-->
<a name="readme-top"></a>


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/{{github_user}}/{{playbook_name}}">
    <img src="{{my_url}}/images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">{{playbook_name}}</h3>

  <p align="center">
    {{playbook_details}} 
    <br />
    <a href="https://github.com/{{github_user}}/{{playbook_name}}"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/{{github_user}}/{{playbook_name}}">View Demo</a>
    ·
    <a href="https://github.com/{{github_user}}/{{playbook_name}}/issues">Report Bug</a>
    ·
    <a href="https://github.com/{{github_user}}/{{playbook_name}}/issues">Request Feature</a>
  </p>
</div>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]]({{my_url}}/github/{{playbook_name}}/scr_{{playbook_name}}.jpg)

There are many great README templates available on GitHub; however, I didn't find one that really suited my needs so I created this enhanced one. I want to create a README template so amazing that it'll be the last one you ever need -- I think this is it.

Here's why:
* Your time should be focused on creating something amazing. A project that solves a problem and helps others
* You shouldn't be doing the same tasks over and over like creating a README from scratch
* You should implement DRY principles to the rest of your life :smile:

Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people have contributed to expanding this template!

Use the `BLANK_README.md` to get started.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

This playbook is created for ansible. The language for Ansible is YAML. 

* [![yaml][yaml-logo]][yaml-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This playbook is created for Ansible version core 2.15.0 
This is an example of how to list things you need to use the software and how to install them.
* Check in your terminal
  ```sh
  ansible --version
  ```

### Installation

_You can clone this project with the following command._


1. Clone the repo
   ```sh
   git clone https://github.com/{{github_user}}/ansible.git
   ```


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

To use a playbook from my collection go to the directory you cloned the repo and then go to the directory of the playbook you want to run. 
Change the variables to your needs in /vars/main.yml. Change the host you want to run it against in /playbook_name/inventory or delete the file if
u use a centralized inventory file. 



<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- CONTACT -->
## Contact

Jouke Siekman - [@JoukeSiekman]({{my_twitter}}) - {{my_email}}

Project Link: [https://github.com/{{github_user}}/ansible](https://github.com/{{github_user}}/ansible)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Support me

Would you like to support me. Thats really nice you can support me by the following ways:

["Buy Me A Coffee"]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/jouke-siekman/
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
[yaml-logo]: https://img.shields.io/badge/yaml-000000?style=for-the-badge&logo=yaml&logoColor=blue
[yaml-url]: https://yaml.org
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/siekman)
