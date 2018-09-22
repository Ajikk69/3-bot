u3a30e49a53a2ab0e746546a1b8340c0a


elif msg.text in ["Bot out"]:
  if msg._from in owner:
    gid = k1.getGroupIdsJoined()
    gid = k2.getGroupIdsJoined()
    gid = k3.getGroupIdsJoined()
    gid = k4.getGroupIdsJoined()
    gid = k5.getGroupIdsJoined()
    gid = k6.getGroupIdsJoined()
    gid = k7.getGroupIdsJoined()
    gid = k8.getGroupIdsJoined()
    gid = k9.getGroupIdsJoined()
    gid = k10.getGroupIdsJoined()
    for i in gid:
      k10.leaveGroup(i)
      k9.leaveGroup(i)
      k8.leaveGroup(i)
      k7.leaveGroup(i)
      k6.leaveGroup(i)
      k5.leaveGroup(i)
      k4.leaveGroup(i)
      k3.leaveGroup(i)
      k2.leaveGroup(i)
      k1.leaveGroup(i)
    if wait["lang"] == "JP":
      k1.sendMessage(msg.to,"Semua Bot Sudah Keluar")
    else:
      k1.sendMessage(msg.to,"He declined all invitations")


© J1KK
