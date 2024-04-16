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
  GIT_TAG origin/main
  DEPENDS mc_rtc
)

AddProject(joystickPlugin
  GITHUB antodld/mc_joystick_plugin
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

AddCatkinProject(puppet_description
  GITHUB antodld/puppet_description
  GIT_TAG origin/main
  WORKSPACE data_ws
)

AddProject(mc_biRobotTeleop
  GITHUB adallard/mc_biRobotTeleop
  GIT_TAG origin/main
  DEPENDS mc_rtc biRobotTeleop_utils puppet contact_estimation joystickPlugin openVrPlugin UDPDataLink
)


