# Copyright (C) 2008-2013 TrinityCore <http://www.trinitycore.org/>
#
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without
# modifications, as long as this notice is preserved.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

set(scripts_STAT_SRCS
  ${scripts_STAT_SRCS}
  Custom/VendorScript.cpp
  Custom/Supporter.cpp
  Custom/Teleporter.cpp
  Custom/GurubashiEvent.cpp
  Custom/Transmogrification.h
  Custom/Transmogrification.cpp
  Custom/ArenaFastStart.cpp
  Custom/ArenaSpectate.cpp
  Custom/ChangeToken.cpp
  Custom/PvPIsleScript.cpp
  Custom/arenaquecom.cpp
  Custom/beastmaster.cpp
  Custom/enchanter.cpp
  Custom/KillStreak.cpp
  Custom/mmr.cpp
  Custom/morph.cpp
  Custom/npcdoctor.cpp
  Custom/proffession.cpp
)

message("  -> Prepared: Custom")
