# Tailwind CSS Production Build Issue

This repository demonstrates an uncommon bug encountered with Tailwind CSS where styles defined using Tailwind classes fail to apply after the production build process.  Development mode functions correctly, but the issue arises when building for production.

The root cause appears to be related to a misconfiguration or conflict within the build pipeline, potentially involving the order of operations or a missing dependency, as the issue was resolved by adding a specific postcss plugin.