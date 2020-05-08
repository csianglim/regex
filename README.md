# (?s)\"conference\"(.*?)\Kjournal\: \K\"(?!in)(.*?)\"$

- (?s) - Match multiline
- Starts with \"conference\"
- (.*?) - Match everything after conference until journal
- \K Kill match before journal
- (?!in) - journal entry doesn't start with in
