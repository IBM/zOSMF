---
layout: default
---

<div class="greybackground">
  <section id="main_content" class="inner">
    <h1>News</h1>
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
    <a href="#" class="show-previous-news">Show previous news...</a>
    <div class="previous-news" style="display: none">
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
    <p>IBM z/OS Management Facility (z/OSMF) provides a framework for managing various aspects of a z/OS system through a task oriented, Web browser interface. By streamlining some traditional tasks and automating others, z/OSMF can help to simplify some areas of system management and reduce the level of expertise needed for managing a system.</p>
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
    <p>IBM Z Software Trials (zTrial) provides a no-charge trial for z/OSMF without installation required:</p>
    <button><a href="{{ site.url_zosmf_trial }}" target="_blank">z/OSMF Trial</a></button>
    <p>You can also go to the GitHub repository to download the demonstration of z/OSMF functions:</p>
    <button><a href="{{ site.url_zosmf_sample_code }}" target="_blank">z/OSMF GitHub</a></button>
    <p>Here are a series of tutorial videos and online courses for z/OSMF plugins:</p>
    <div class="div_img">
      <!-- <div>
        <p><a href="{{ site.url_video_zosmf_dataset }}" target="_blank"><img src="{{ site.img_video_zosmf_dataset }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_dataset }}" target="_blank">{{ site.title_video_zosmf_dataset }}</a></p>
      </div> -->
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
        <p><a href="{{ site.url_video_zosmf_rest_api_tso }}" target="_blank"><img src="{{ site.img_video_zosmf_rest_api_tso }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_rest_api_tso }}" target="_blank">{{ site.title_video_zosmf_rest_api_tso }}</a></p>
      </div>
      <div>
        <p><a href="{{ site.url_video_zosmf_rest_api_dataset }}" target="_blank"><img src="{{ site.img_video_zosmf_rest_api_dataset }}"/></a></p>
        <p><a href="{{ site.url_video_zosmf_rest_api_dataset }}" target="_blank">{{ site.title_video_zosmf_rest_api_dataset }}</a></p>
      </div>
    </div>
  </section>
</div>

<div class="bluebackground">
  <section id="main_content" class="inner">
    <h1 id="documentation">Documentation</h1>
    <p>We provide some expert documentations for you to learn more about z/OSMF:</p>
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
    <p><li>Other documentations:</li></p>
    <button><a href="{{ site.url_cics_content_solution }}" target="_blank">CICS Content Solution</a></button>
  </section>
</div>

<div class="whitebackground">
  <section id="main_content" class="inner">
    <h1 id="community">Community</h1>
    <p>We provide a worldwide community which offers business and technical experts, blogs and forums to exchange ideas, connect through shared interests and develop expertise:</p>
    <button><a href="{{ site.url_zosmf_community }}" target="_blank">z/OSMF Community</a></button>
  </section>
</div>

<div class="bluebackground">
  <section id="main_content" class="inner">
    <h1 id="user-reference">User Reference</h1>
    <p>Following cases will show you how customers benefit from z/OSMF:</p>
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
    <p>The <em>zosmf-adoption</em> Channel on Slack is provided for open discussion on configuration, adoption, marketing, and events for z/OSMF product.</p>
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
