# GLT-1
GLT (Gougle Language Transformer) - 1 is the first version a language AI model developped by Gougle based to GPT-3.5-Turbo/GPT-4.

# Usages
To use GLT-1, you can use `pip` for `python` or `cdn` to `javascript`.<br>
With `pip` in `cmd` :<br>
```
pip install gougleai
```
Or with `cdn` in `html` page :<br>
```
<script src="https://api.withgougle.cf/ai/glt/1" type="text/javascript"></script>
```

# Exemple
## In `python` :<br>
```
import gougleai

modelsList = gougleai.models.list

print(modelsList)

model = gougleai.models.glt.1
prompt = "Hello ! I'm Gougle."

response = gougleai.complete(model = model, prompt = prompt, tokenNumber = 100)

print(respnse.choice[2].text)
```

### Output :<br>
```
"GLT-1: gougleai.models.glt.1"
"Hello Gougle ! What can I do for you today ?"
```

## In `javascript` :<br>
```
const modelsList = gougleai.models.list;

console.log(modelsList);

const model = gougleai.models.glt.1;
const prompt = "Hello Gougle User ! I just want to talk with you.";

const response = gougleai.complete(model, prompt, 100);

console.log(response.choice[2].text);
```

### Output :<br>
```
"GLT-1: gougleai.models.glt.1"
"Ok, me too I just want to talk with you !"
```
