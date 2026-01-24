# arch-repo
Repository for archlinux.

Add to /etc/pacman.conf :
<pre><code>
[misak-repo]
Server = https://github.com/misak0007/arch-repo/raw/refs/heads/main/$arch
SigLevel = Never
 </code></pre>
 
Download repository :
<pre><code>
git clone git@github.com:misak0007/arch-repo.git
cd arch-repo
git lfs install --local
git lfs pull
</code></pre>

