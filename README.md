# mob
A simple script to add 2 co-authors to git commits. 

To use:
- Copy mob to a directory in your $PATH
- run `chmod +x mob`

Export the co-authors details - ie
- `export MOBBER_1=Joe Bloggs <joe.bloggs@engineerbetter.com>`
- `export MOBBER_1=Jane Bloggs <jane.bloggs@engineerbetter.com>`

Once set, run `mob your commit message` to make a commit with the 2 co-authors included.
