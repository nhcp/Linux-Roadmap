Practical Linux Command Line Learning Roadmap
Beginner Level
1. Basic Navigation & File Management
pwd: Show current directory
ls, ls -l, ls -a: List files and directories
cd: Change directory
tree: Visualize directory structure
touch: Create empty files
mkdir, rmdir: Create and remove directories
cp, mv, rm: Copy, move, and delete files/directories
2. Viewing & Editing Files
cat: Concatenate and display file content
less, more: View file content page by page
head, tail: View the beginning/end of files
nano, vi/vim: Basic text editing
3. User & Group Basics
whoami: Show current user
id: Show user and group IDs
adduser, useradd: Add new users
passwd: Set/change user password
su, sudo: Switch user, run as superuser
4. Permissions & Ownership
chmod: Change file permissions
chown: Change file owner
chgrp: Change file group
umask: Default permission mask
5. Getting Help
man: Manual pages for commands
--help: Command-specific help
info: Extended documentation
Intermediate Level
6. Process Management
ps, ps -ef, ps aux: List processes
top, htop: Real-time process monitoring
pgrep, pkill: Find/kill processes by name
kill, killall: Terminate processes by PID or name
jobs, bg, fg: Manage background/foreground jobs
7. Searching & Filtering
grep: Search text using patterns
find: Search for files and directories
locate: Quickly find files by name
which, whereis: Locate executables
awk, sed: Advanced text processing
cut, sort, uniq, wc: Manipulate and analyze text
8. File Compression & Archiving
tar: Archive files
gzip, gunzip: Compress/decompress files
zip, unzip: Zip archive management
9. Networking Basics
ping: Test network connectivity
ifconfig, ip: Network interface configuration
netstat, ss: Network statistics and sockets
curl, wget: Download files from the internet
scp, sftp: Secure file transfer
ssh: Secure shell access
10. Disk Usage & Monitoring
df: Disk space usage
du: Directory/file space usage
free: Memory usage
mount, umount: Mount/unmount filesystems
fdisk, lsblk: Disk partitioning and block devices
11. Package Management
apt, apt-get: Debian/Ubuntu package management
yum, dnf: RedHat/CentOS/Fedora package management
snap: Universal Linux packages
dpkg, rpm: Low-level package tools
Advanced Level
12. Shell Scripting
Writing bash scripts: Shebang, variables, loops, conditionals, functions
Script permissions and execution
Passing arguments to scripts
13. Regular Expressions
grep, sed, awk: Advanced pattern matching and text processing
14. System Services & Daemons
systemctl, service: Manage system services
journalctl: View system logs
systemd basics: Understanding units and targets
15. User & Group Management (Advanced)
usermod, userdel: Modify/delete users
groupadd, groupdel: Manage groups
gpasswd: Group password management
visudo: Edit sudoers file safely
16. Security & Permissions
sudo, su: Privilege escalation
File ACLs: Fine-grained permissions (setfacl, getfacl)
ssh-keygen: SSH key management
ufw, iptables: Firewall configuration
17. Process & Resource Management
nice, renice: Adjust process priority
ulimit: User resource limits
lsof: List open files
strace: Trace system calls
18. Networking (Advanced)
ssh tunneling: Secure port forwarding
rsync: Efficient file synchronization
netcat (nc): Network debugging and data transfer
nmap: Network scanning and security auditing
19. Automation & Scheduling
cron: Scheduled tasks
at, anacron: One-time and recurring jobs
20. Version Control
git: Source code management (init, clone, add, commit, push, pull, branch, merge, log, status, diff)
21. Monitoring & Logging
tail -f: Real-time log monitoring
dmesg: Kernel ring buffer messages
watch: Periodically run a command
uptime, vmstat, iostat: System performance
