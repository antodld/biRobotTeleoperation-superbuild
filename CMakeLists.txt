AddProject(biRobotTeleop_utils
  GITHUB antodld/biRobotTeleopTask
  GIT_TAG origin/main
  DEPENDS mc_rtc
)

AddProject(UDPDataLink
  GITHUB antodld/UDPDataLink
  GIT_TAG origin/main
)

AddProject(openVrPlugin
  GITHUB antodld/mc_OpenVR_plugin
  GIT_TAG origin/master
  DEPENDS mc_rtc
)

AddProject(contact_estimation
  GITHUB antodld/mc_contact_estimation
  GIT_TAG origin/master
  DEPENDS mc_rtc
)

AddProject(puppet
  GITHUB antodld/mc_puppet
  GIT_TAG origin/main
  DEPENDS mc_rtc
)

AddProject(puppet_description
  GITHUB antodld/puppet_description
  GIT_TAG origin/main
  DEPENDS mc_rtc
)

AddProject(mc_BiRobotTeleop
  GITHUB adallard/mc_biRobotTeleop
  GIT_TAG origin/main
  DEPENDS biRobotTeleop_utils puppet
)


