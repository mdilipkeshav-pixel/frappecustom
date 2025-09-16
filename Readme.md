frappecustom:baremetal

From another machine, you can pull it with:

echo $CR_PAT | docker login ghcr.io -u mdilipkeshav-pixel --password-stdin
docker pull ghcr.io/mdilipkeshav-pixel/frappecustom:bare-metal


($CR_PAT is your GitHub Personal Access Token with read:packages permission).



Docker 
docker pull ghcr.io/mdilipkeshav-pixel/frappecustom:full




docker compose up -d
