(note: forked from [this repo](https://github.com/hzik/kontent-custom-element-summernote))

# Summernote Rich Text Editor
This is a [custom element](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features) for [Kentico Kontent](https://kontent.ai) that allows users to use the [Summernote rich text editor](https://summernote.org/).

![Screenshot of custom element](SummernoteRichTextEditor.gif)

## Setup

1. Follow the instructions in the [Kentico Kontent documentation](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features#a-3--displaying-a-custom-element-in-kentico-kontent) to add the element to a content model.
    * The `Hosted code URL` is where https://html-kontent.furman.dev/
    * No JSON parameters are necessary

## Deploying

This app is already deployed at https://html-kontent.furman.dev/ via github pages, but you can host it yourself if you'd like as well.

## What is Saved?

```json
"summernote": {
        "type": "custom",
        "name": "summernote",
        "value": "<h1>Some heading</h1><p><b>lorem ipsum</b></p><pre>code sample</pre><ul><li>item 1</li><li>item 2</li><li>item 3</li></ul><p><br></p><table class=\"table table-bordered\"><tbody><tr><td>cell 1</td><td>cell 2<br></td></tr><tr><td>cell 3<br></td><td>cell 4<br></td></tr></tbody></table><p><br></p>"
      }
```

