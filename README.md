Docker build file to create an image that can be used to build
MiSTer cores on Apple Silicon Macs.

Key difference is the adm/qenv.sh script to remove the check for
SSE instruction support which is there when using Rosetta.
