# scorch

Use underscore for creating files from a template

I needed to have file templating for some systems responsibilities and
I didn't feel like learning m4 or some other horrible language. I like
underscore templates and they work for me.

Install it like:

    npm install -g scorch

Run it like:

    scorch template.tmpl data.json > result.yourfile

To use the environment variables as your data, run it like this:

    scorch -e template.tmpl > result.yourfile

## License

Copyright 2013 E14N https://e14n.com/
Copyright 2015 Fuzzy.io https://fuzzy.io/

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
