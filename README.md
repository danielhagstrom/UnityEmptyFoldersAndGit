# UnityEmptyFoldersAndGit
Simple git-hook to look through the added files for a commit and try to determine if you're adding empty folders. There are some assumptions built in, such as no periods in folder names.

Another alternative to this is simply ignoring all meta files of folders (not covered by this hook), as AFAIK .meta files for folders are essentially "useless", in that they have no practical function for the Unity game engine.
