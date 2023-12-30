# 🇮🇩SCRIPT BY DANSVPN🇮🇩
# Langkah pertama khusus os debian
<code><pre>apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot</code></pre>
# INSTALL SCRIPT
<code><pre>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/Scvpn/vip1/main/memek.sh && chmod +x memek.sh && sed -i -e 's/\r$//' memek.sh && screen -S memek ./memek.sh</code></pre>
# FIX SSH
<code><pre>wget -q -O fix "https://raw.githubusercontent.com/xsm-syn/fix/main/ws-700.sh" && bash fix</code></pre>
# UPDATE MANUAL SCRIPT
<code><pre>wget -q https://raw.githubusercontent.com/Scvpn/vip1/main/update.sh && chmod +x update.sh && sed -i -e 's/\r$//' update.sh && screen -S update ./update.sh</code></pre>
