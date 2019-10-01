+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Data Engineer Intern"
  company = "Wildlife Studios"
  company_url = "https://wildlifestudios.com/en"
  location = "São Paulo, Brazil"
  date_start = "2017-04-15"
  date_end = "2017-08-15"
  description = """
    * Designed and implemented a data pipeline for real-time processing, storage, and visualization of several metrics of interest, such as a count of app crashes, new installs, active online users, and others.
    * Installed, configured, and benchmarked the company's first Spark cluster, enabling engineers to run data processing pipelines and train Machine Learning models over a cluster of machines.
    * Analyzed the number of impressions, clicks, and installs of users across multiple games and AdNets, leading to an improvement in user targeting and an increase in the installs-to-impressions ratio.
  """

[[experience]]
  title = "Research Intern"
  company = "UC Berkeley"
  company_url = ""
  location = "California, United States"
  date_start = "2016-03-15"
  date_end = "2016-07-15"
  description = """
    * Surveyed the State-of-the-Art in Neural Networks and Reinforcement Learning.
    * Designed and trained an adaptive traffic lights controller, capable of adapting the distribution of green time over different lanes with varying vehicle throughput. The controller was trained using Reinforcement Learning techniques and Neural Networks.
    * Our adaptive controller achieved a reduction of more than 25% on the average number of idle vehicles over fixed-time controllers.
  """

+++
