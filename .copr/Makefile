srpm:
	dnf --nogpgcheck -y install rpkg --repofrompath=repo,https://copr-be.cloud.fedoraproject.org/results/clime/rpkg-client/fedora-26-x86_64/
	echo '%dist %{nil}' > ~/.rpmmacros
	rpkg srpm --outdir=$(outdir) --spec=$(spec)
