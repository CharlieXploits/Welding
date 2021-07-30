# Welding Högstadiet
# Steg 1,
Knapp Tryck
```lua
KeyBind(<Knapp>,function()

end)
```
# Steg 2,
Frames
```lua
Frame(Wait,Frames,TimePerFrame,callback)
```
# Steg 3,
Animation Exempel
```lua
while Humanoid.Health > 0 do
    swait()
    local TORSOVELOCITY = (RootPart.Velocity * VT(1, 0, 1)).magnitude
    local TORSOVERTICALVELOCITY = RootPart.Velocity.y
  if TORSOVELOCITY > 1 and ATTACK == false then -- walk anim
    RightShoulder.C0=RightShoulder.C0:Lerp(RightShoulderOrigin*CFrame.new(math.rad(0),math.rad(0),math.rad(0))*CFrame.Angles(math.rad(0),math.rad(0),math.rad(0)),0.1)
    LeftShoulder.C0=LeftShoulder.C0:Lerp(LeftShoulderOrigin*CFrame.new(math.rad(0),math.rad(0),math.rad(0))*CFrame.Angles(math.rad(0),math.rad(0),math.rad(0)),0.1)
  RightHip.C0=RightHip.C0:Lerp(RightHipOrigin*CFrame.new(math.rad(0),math.rad(0),math.rad(0))*CFrame.Angles(math.rad(0),math.rad(0),math.rad(0)),0.1)
  LeftHip.C0=LeftHip.C0:Lerp(LeftHipOrigin*CFrame.new(math.rad(0),math.rad(0),math.rad(0))*CFrame.Angles(math.rad(0),math.rad(0),math.rad(0)),0.1)
  RootJoint.C0=RootJoint.C0:Lerp(RootJointOrigin*CFrame.new(math.rad(0),math.rad(0),math.rad(0))*CFrame.Angles(math.rad(0),math.rad(0),math.rad(0)),0.1)
  elseif TORSOVELOCITY < 1 and ATTACK == false then -- no walk
        RightShoulder.C0=RightShoulder.C0:Lerp(RightShoulderOrigin*CFrame.new(math.rad(0),math.rad(0),math.rad(0))*CFrame.Angles(math.rad(0),math.rad(0),math.rad(0)),0.1)
    LeftShoulder.C0=LeftShoulder.C0:Lerp(LeftShoulderOrigin*CFrame.new(math.rad(0),math.rad(0),math.rad(0))*CFrame.Angles(math.rad(0),math.rad(0),math.rad(0)),0.1)
  RightHip.C0=RightHip.C0:Lerp(RightHipOrigin*CFrame.new(math.rad(0),math.rad(0),math.rad(0))*CFrame.Angles(math.rad(0),math.rad(0),math.rad(0)),0.1)
  LeftHip.C0=LeftHip.C0:Lerp(LeftHipOrigin*CFrame.new(math.rad(0),math.rad(0),math.rad(0))*CFrame.Angles(math.rad(0),math.rad(0),math.rad(0)),0.1)
  RootJoint.C0=RootJoint.C0:Lerp(RootJointOrigin*CFrame.new(math.rad(0),math.rad(0),math.rad(0))*CFrame.Angles(math.rad(0),math.rad(0),math.rad(0)),0.1)
end
end
```
