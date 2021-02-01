---
layout: default
---

<div class="greybackground">
  <section id="main_content" class="inner">
    <h1>News</h1>
    <p><strong>Check out <a href="{{ site.url_video_zosmf_ansible_collection }}" target="_blank">our latest video</a> about z/OSMF Ansible collection.</strong></p>
    <p><strong>Check out our sample Ansible playbooks for automating 3 different z/OS use cases at <a href="{{ site.url_zosmf_ansible_github_usecase }}" target="_blank">here</a>!</strong></p>
    <p><strong>z/OSMF enhancements in 4Q 2020:</strong></p>
    <p><li>z/OSMF Ansible collection is enhanced to support MVS operator commands as well as fetching sequential data set or PDS/E data set member.</li></p>
    <p><li>z/OSMF Desktop is enhanced by PH28692 to support typeahead search. PH30398 also enhances z/OSMF Desktop to support creating data set. Clients can create a new physical sequential or partitioned data set based on an existing data set, a predefined template, or fully specified attributes.</li></p>
    <p><li>z/OSMF REST data set and file API is enhanced by APAR PH29745 to queue concurrent requests from the same user when the number of TSO address spaces are exhausted. A tuning guide for REST data set and file API is also published at <a href="{{ site.url_zosmf_dataset_api_tuning_guide }}" target="_blank">here</a>.</li></p>
    <p><li>z/OS Operator Consoles plugin is enhanced by PH30881 to support side view for WTOR/Hold messages.</li></p>
    <p><li>z/OSMF is enhanced by PH30398 to support 15 minutes as the minimum expiration time of z/OSMF user session.</li></p>
    <p><li>z/OSMF Diagnostic Assistant is enhanced with PH25691 to support the display of z/OSMF data file system utilization on the z/OSMF desktop taskbar. It  also supports automatic cleanup of z/OSMF diagnostic data based on a predefined policy.</li></p>
    <p><li>z/OSMF Workflow Engine has several enhancements with the PTF for APAR PH28532. The workflow administrator can delete multiple workflow instances at a time. To perform a workflow on a remote sysplex, a single sign-on among z/OSMF instances is no longer strictly required. In the absence of a single sign-on, the request prompts for a user and password, if necessary. The "create new workflow instance" dialog now exploits the typeahead search for the workflow definition and workflow properties files. This can eliminate the need to provide the full data set name or path name.</li></p>
    <p><li>z/OSMF startup time and resource consumption during startup is improved with the PTFs for APARs PH28921, PH28920, PH28971, PH28990, PH28451, PH29230, PH29243, PH28832, and PH28872. Actual results can vary, depending on the client's configuration.</li></p>
    <p><li>Cloud Provisioning and Management (CP&M) for z/OS continues to deliver many new functions and improved user experience via continuous delivery. The following features were delivered on December 10, 2020 with PTFs UI72944 (z/OS V2.3) and UI72945 (z/OS V2.4) to expand CP&M provisioning capability and offer a robust software provisioning platform on z/OS. Please refer to our <a href="{{ site.url_cpm_enhancement }}" target="_blank">latest blog</a> for details.<p><li>
    <a href="#" class="show-previous-news">Show previous news...</a>
    <div class="previous-news" style="display: none">
      <p><strong>z/OSMF startup improvement is now available:</strong></p>
      <p><li>With the new PTFs we delivered for startup improvement, in lab measurements of a small z15 lpar, the startup time improved about 50%. Please refer to our <a href="{{ site.url_zosmf_startup_improvement }}" target="_blank">latest blog</a> for details.</li></p>
      <p><strong>Check out <a href="{{ site.url_zosmf_client_certificate }}" target="_blank">this blog</a> about how to access z/OSMF with client certificate.</strong></p>
      <p><strong>z/OSMF Lite Stage 2 is now available:</strong></p>
      <p><li>z/OSMF Lite provides the flexibility to tailor z/OSMF runtime for better performance in a few clicks. With z/OSMF Lite, you can improve up to 50% startup performance. Please refer to our <a href="{{ site.url_tailor_zosmf_server }}" target="_blank">latest blog</a> for details.</li></p>
      <p><strong>z/OSMF enhancements in 2Q 2020:</strong></p>
      <p><li>z/OSMF REST Jobs API is enhanced by APAR PH23046 to support search option and codepage conversion for spool outputs. Additional option is also introduced to return active jobs only and additional data like submit time.</li></p>
      <p><li>z/OSMF REST data set and file API is enhanced by APAR PH22030 to support "Allocate Like". Response time is also improved for retrieving content from large data set or USS file by supporting "Accept-Encoding: gzip" header.</li></p>
      <p><li>User can create link on z/OSMF desktop with APAR PH24527. With this APAR, the VS Code like editor included in z/OSMF desktop is also enhanced to support syntax highlight for JCL, XML, HTML and REXX content.</li></p>
      <p><li>z/OSMF Workflow Editor is enhanced with APAR PH24190 to use the z/OSMF integrated VS Code like editor, when working with large amounts of text. This could leverage benefits of the z/OSMF editor such as easy to do find and replace, preview support, syntax highlighting, etc.</li></p>
      <p><li><a href="{{ site.url_zosmf_ansible_galaxy }}" target="_blank">z/OSMF Ansible collection</a> is enhanced to support z/OS job operations based on z/OSMF REST Jobs API.</li></p>
      <p><li>APAR PH24527 provides more flexibility to customize z/OSMF runtime in terms of which services to be started. User can now use a simple GUI panel or a json file to easily enable/disable most z/OSMF services for lightweight purpose.</li></p>
      <p><li>User can use "SETIZU" or "SET IZU" command to dynamically change values of z/OSMF parmlib options instead of having to restart z/OSMF. This is provided by APAR PH24088.</li></p>
      <p><li>z/OSMF Workflow is enhanced by PH21919 to support saving all job outputs in specified USS directory and also displaying the path of workflow definition. In addition, PH24190 also enhances workflow to support automatic deletion when workflow is completed.</li></p>
      <p><li>z/OS Operator Console plugin is enhanced by PH24072 to allow setup console attributes from z/OSMF UI instead of having to create several security configuration.</li></p>
      <p><li>z/OSMF Diagnostic Assistant is further enhanced by PH18776 to support changing z/OSMF logging level from z/OSMF GUI. Combine with previous support to download z/OSMF diagnostic data with a few clicks, z/OSMF Diagnostic Assistant intends to simplify the diagnostic process of z/OSMF.</li></p>
      <p><strong>z/OSMF Ansible collection is now available on Ansible Galaxy:</strong></p>
      <p><li><a href="{{ site.url_zosmf_ansible_galaxy }}" target="_blank">z/OSMF Ansible collection</a> helps you to integrate Ansible and z/OS without any environment change to z/OS. Please refer to our <a href="{{ site.url_leveraging_zosmf_ansible }}" target="_blank">latest blog</a> for details.</li></p>
      <p><strong>z/OSMF enhancements in 4Q 2019:</strong></p>
      <p><li>z/OSMF Security Configuration Assistant is enhanced to support variable substitution and validation by user group with APAR PH17871.</li></p>
      <p><li>z/OSMF Desktop is enhanced by APAR PH16076 to support searching, browsing and editing USS file and directory from the same place where user can do similar operation with data sets today. User can also submit data set or USS file as JCL and check job output directly from the z/OSMF desktop editor or search window.</li></p>
      <p><li>z/OSMF Workflows tasks is enhanced to support creating workflow instance from workflow definition located in remote systems by APAR PH14185.</li></p>
      <p><li>z/OSMF REST data set and file service is enhanced to support accessing data sets and files in remote system by APAR PH15263.</li></p>
      <p><li>z/OSMF supports JSON Web Token (JWT) by returning JWT token during authentication and accepting JWT token for authorization of z/OSMF services by APAR PH12143.</li></p>
      <p><li>z/OSMF Sysplex Management plugin is enhanced by PH15554 to allow users to create a new couple data set for several operations like set Primary CDS, switch Alternate CDS to Primary CDS, etc.</li></p>
      <p><li>z/OSMF startup time is reduced by APAR PH19227 and PH06678.</li></p>
      <p><strong>z/OSMF V2R4 is now available in Sep 2019:</strong></p>
      <p><li>Please refer to <a href="{{ site.url_share_fort_worth }}" target="_blank">the latest handout from SHARE Fort Worth</a> or <a href="{{ site.url_zos_v2r4_announcement }}" target="_blank">z/OS V2R4 Announcement</a>.</li></p>
      <a href="#" class="hide-previous-news">Hide previous news...</a>
    </div>
  </section>
</div>

<div class="bluebackground">
  <section id="main_content" class="inner">
    <h1 id="what">About z/OSMF</h1>
    <p>IBM z/OS Management Facility (z/OSMF) provides a framework for managing various aspects of a z/OS system through a task-oriented, web browser interface. By streamlining some traditional tasks and automating others, z/OSMF can help to simplify some areas of system management and reduce the level of expertise that is needed for managing a system.</p>
    <p><li>Learn more about z/OSMF:</li></p>
    <button><a href="{{ site.url_zosmf_knowledge_center }}" target="_blank">z/OSMF Knowledge Center</a></button>
    <div class="div_space"></div>
    <button><a href="{{ site.url_video_zosmf_overview }}" target="_blank">{{ site.title_video_zosmf_overview }}</a></button>
    <p><li>Explore spotlights and key features of z/OSMF:</li></p>
    <button><a href="{{ site.url_zosmf_marketplace }}" target="_blank">z/OSMF Marketplace</a></button>
  </section>
</div>

<div class="whitebackground">
  <section id="main_content" class="inner">
    <h1 id="how">Get Started</h1>
    <p>The IBM Z software trials program provides a no-charge trial for z/OSMF that does not require installation:</p>
    <button><a href="{{ site.url_zosmf_trial }}" target="_blank">z/OSMF Trial</a></button>
    <p>The IBM-Z-zOS GitHub repository provides demonstrations of z/OSMF functions that you can download:</p>
    <button><a href="{{ site.url_zosmf_sample_code }}" target="_blank">z/OSMF GitHub</a></button>
    <p>IBM provides a series of tutorial videos and online courses to help you learn more about specific z/OSMF tasks:</p>
    <div class="div_img">
      <div>
        <p><a href="{{ site.url_video_zosmf_dataset_ussfile }}" target="_blank"><img src="{{ site.img_video_zosmf_dataset_ussfile }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_dataset_ussfile }}" target="_blank">{{ site.title_video_zosmf_dataset_ussfile }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_import_manager }}" target="_blank"><img src="{{ site.img_video_zosmf_import_manager }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_import_manager }}" target="_blank">{{ site.title_video_zosmf_import_manager }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_workflows }}" target="_blank"><img src="{{ site.img_video_zosmf_workflows }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_workflows }}" target="_blank">{{ site.title_video_zosmf_workflows }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_capacity_provisioning }}" target="_blank"><img src="{{ site.img_video_zosmf_capacity_provisioning }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_capacity_provisioning }}" target="_blank">{{ site.title_video_zosmf_capacity_provisioning }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_software_services }}" target="_blank"><img src="{{ site.img_video_zosmf_software_services }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_software_services }}" target="_blank">{{ site.title_video_zosmf_software_services }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_zos_operator_consoles }}" target="_blank"><img src="{{ site.img_video_zosmf_zos_operator_consoles }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_zos_operator_consoles }}" target="_blank">{{ site.title_video_zosmf_zos_operator_consoles }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_workload_management }}" target="_blank"><img src="{{ site.img_video_zosmf_workload_management }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_workload_management }}" target="_blank">{{ site.title_video_zosmf_workload_management }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_incident_log }}" target="_blank"><img src="{{ site.img_video_zosmf_incident_log }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_incident_log }}" target="_blank">{{ site.title_video_zosmf_incident_log }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_sysplex_management }}" target="_blank"><img src="{{ site.img_video_zosmf_sysplex_management }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_sysplex_management }}" target="_blank">{{ site.title_video_zosmf_sysplex_management }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_security_configuration_assistant }}" target="_blank"><img src="{{ site.img_video_zosmf_security_configuration_assistant }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_security_configuration_assistant }}" target="_blank">{{ site.title_video_zosmf_security_configuration_assistant }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_network_configuration_assistant }}" target="_blank"><img src="{{ site.img_video_zosmf_network_configuration_assistant }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_network_configuration_assistant }}" target="_blank">{{ site.title_video_zosmf_network_configuration_assistant }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_zert_network_analyzer }}" target="_blank"><img src="{{ site.img_video_zosmf_zert_network_analyzer }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_zert_network_analyzer }}" target="_blank">{{ site.title_video_zosmf_zert_network_analyzer }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_rest_api_tso }}" target="_blank"><img src="{{ site.img_video_zosmf_rest_api_tso }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_rest_api_tso }}" target="_blank">{{ site.title_video_zosmf_rest_api_tso }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_rest_api_dataset }}" target="_blank"><img src="{{ site.img_video_zosmf_rest_api_dataset }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_rest_api_dataset }}" target="_blank">{{ site.title_video_zosmf_rest_api_dataset }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_ansible_collection }}" target="_blank"><img src="{{ site.img_video_zosmf_ansible_collection }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_ansible_collection }}" target="_blank">{{ site.title_video_zosmf_ansible_collection }}</a></p>
      </div>
    </div>
  </section>
</div>

<div class="bluebackground">
  <section id="main_content" class="inner">
    <h1 id="documentation">Documentation</h1>
    <p>IBM provides some expert documentation to help you learn more about z/OSMF:</p>
    <button><a href="{{ site.url_zosmf_configuration_guide }}" target="_blank">z/OSMF Configuration Guide</a></button>
    <div class="div_space"></div>
    <button><a href="{{ site.url_zosmf_programming_guide }}" target="_blank">z/OSMF Programming Guide</a></button>
    <div class="div_space"></div>
    <button><a href="{{ site.url_zosmf_redbook }}" target="_blank">z/OSMF Redbook</a></button>
    <div class="div_space"></div>
    <button><a href="{{ site.url_zosmf_apars }}" target="_blank">z/OSMF New Function APARs</a></button>
    <p><li>Learn more about z/OSMF Workflows:</li></p>
    <button><a href="{{ site.url_zosmf_zorow }}" target="_blank">z/OS Open Repository of Workflows</a></button>
    <p><li>Learn more about IBM Cloud Provisioning and Management for z/OS (CP&M):</li></p>
    <button><a href="{{ site.url_zosmf_cpm_content_solution }}" target="_blank">CP&M Content Solution</a></button>
    <div class="div_space"></div>
    <button><a href="{{ site.url_zosmf_cpm_knowledge_center }}" target="_blank">CP&M Knowledge Center</a></button>
    <div class="div_space"></div>
    <button><a href="{{ site.url_zosmf_cpm_trial }}" target="_blank">CP&M Trial</a></button>
    <p><li>Other documentation:</li></p>
    <button><a href="{{ site.url_cics_content_solution }}" target="_blank">CICS Content Solution</a></button>
  </section>
</div>

<div class="whitebackground">
  <section id="main_content" class="inner">
    <h1 id="community">Community</h1>
    <p>The IBM Z and LinuxONE Community provides business and technical experts around the world the ability to exchange ideas, develop expertise, and connect through shared interests:</p>
    <button><a href="{{ site.url_zosmf_community }}" target="_blank">z/OSMF Community</a></button>
  </section>
</div>

<div class="bluebackground">
  <section id="main_content" class="inner">
    <h1 id="user-reference">User Reference</h1>
    <p>The following cases illustrate how customers benefit from z/OSMF:</p>
    <div class="div_blog">
      <div>
        <button><a href="{{ site.url_blog_icbc }}" target="_blank">{{ site.customer_icbc }}</a></button>
        <div class="div_space"></div>
        <a href="{{ site.url_blog_icbc }}" target="_blank">{{ site.title_blog_icbc }}</a>
      </div>
      <div>
        <button><a href="{{ site.url_blog_vicom_infinity }}" target="_blank">{{ site.customer_vicom_infinity }}</a></button>
        <div class="div_space"></div>
        <a href="{{ site.url_blog_vicom_infinity }}" target="_blank">{{ site.title_blog_vicom_infinity }}</a>
      </div>
      <div>
        <button><a href="{{ site.url_blog_cmb }}" target="_blank">{{ site.customer_cmb }}</a></button>
        <div class="div_space"></div>
        <a href="{{ site.url_blog_cmb }}" target="_blank">{{ site.title_blog_cmb }}</a>
      </div>
    </div>
  </section>
</div>

<div class="whitebackground">
  <section id="main_content" class="inner">
    <h1 id="contact-us">Contact Us</h1>
    <p>The <em>zosmf-adoption</em> channel on Slack is provided for open discussion about configuration, adoption, marketing, and events for the z/OSMF product.</p>
    <button><a href="{{ site.url_zosmf_slack_channel }}" target="_blank">Slack Channel</a></button>
    <!-- <table>
      <tr>
        <th>
          <p>We would like to understand your current experience with z/OSMF. Your feedback will help us improve z/OSMF.</p>
        </th>
        <th>
          <p>The <em>zosmf-adoption</em> Channel on Slack is provided for open discussion on configuration, adoption, marketing, and events for z/OSMF product.</p>
        </th>
      </tr>
      <tr style="text-align:center">
        <th>
          <button><a href="{{ site.url_zosmf_survey }}" target="_blank">z/OSMF Survey</a></button>
        </th>
        <th>
          <button><a href="{{ site.url_zosmf_slack_channel }}" target="_blank">Slack Channel</a></button>
        </th>
      </tr>
    </table> -->
  </section>
</div>
