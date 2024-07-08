# monitor
Internet monitor with auto router reboot on loss of connection

Runs on `Linux chromebox 5.15.0-113-generic #123-Ubuntu SMP Mon Jun 10 08:16:17 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux` as a cron job scheduled every minute.

Auto reboots a Netgear D7000 using telnetenable, see https://openwrt.org/toh/netgear/telnet.console
