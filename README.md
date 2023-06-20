# Expand ext[234] partition

1. `apt install cloud-guest-utils` (`growpart` installation)
2. `growpart /dev/sda 1` (space before partition number)
3. `resize2fs /dev/sda1`
