# Release Notes


> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.

<code style="color : blue">0.1.0</code>

### <span>${\color{#FF9933}0.1.0}$</span>

### <code>0.1.0</code>


markdown-heading

// resets
s { text-decoration:none; } //strike-through
em { font-style: normal; font-weight: bold; } //italic emphasis


// colors
s { color: green }
em { color: blue }

<div class="normal">
    <h1><code>font-style:normal;</code> <small>- Always non-ital</small></h1>
    <p>Should not be ital: <em>Foo</em></p>
    <p class="ital">Should be ital: <em>Foo</em></p>
</div>
<div class="inherit">
    <h1><code>font-style:inherit;</code> <small>- Inherits from parent</small></h1>
    <p>Should not be ital: <em>Foo</em></p>
    <p class="ital">Should be ital: <em>Foo</em></p>
</div>

**Improvement**
* Upgrade the *Search* with `Elasticsearch` to **8.5.1**.
* Update docker-compose files (*elasticsearch.yaml* and *search-compose.yaml*).


<details>
<summary>Tips for collapsed sections</summary>

### You can add a header
You can add text within a collapsed section. 
You can add an image or a code block, too.

```ruby
   puts "Hello World"
```
</details>