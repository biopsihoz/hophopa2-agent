# hophopa2-agent

Release binaries of the HopHopa 2 node agent. The source lives in a private
repository; this one only hosts the builds that `install.sh` downloads.

Every release has `SHA256SUMS`. A node installs a binary only if its sha256
matches the one it was given, so a binary swapped here would not be
installed.
