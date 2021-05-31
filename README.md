# Bracket RP Syntax

## General syntax

The syntax starts with `[/` and ends with `]`. Anything outside will be ignored.

```
[/<action> <target> {target-specific} {modifiers}{; <decor-string>}]
```
`<required>` `{optional}`

---

## Actions `<action>`
Required.

Any verbs can be used as the action, as long as its in the present particple form or present singluar. (`-ing` or `-es` suffix). 

Having only the base form wouldn't make any sense since we also need to do something to the `<target>`.

In the following examples, I'll be using `you` as the target.

Bad examples:
```
[/kiss you]
[/hug you]
[/die you]
```
Good examples:
```
[/kisses you]
[/kissing you]

[/hugs you]
[/hugging you]

[/dies you] looks horrible and incorrect, but valid
[/dying you]
```

**Just make sure that the verb that you will be using would make sense and gramatically sound.**

## Target `<target>`
Required.

Any word can be used as a target, as long as it sounds grammatically correct and makes sense.

The scope is massive, any name, thing, object, place

In the following examples, I will be using various actions and various targets.

```
[/drops phone]
[/ignites self]
[/stabs you]
[/drinks water]
[/snorts cocaine]
```

## Target Specific `{target-specific}`
Optional.

If you want to specify what part of the `<target>` to do your `<action>` on, you can specify them here. Usually separated by a space.

Take a look at this example:
```
[/kisses your lips]
```
`kisses` is the action, `your` is the target and `lips` is the specific.

You cannot use the base pronouns or use simply the noun.

(Bad) Examples:
```
[/kisses you lips]
[/ignites John pants]
[/kills Maria pet]
```

If you are using pronouns, use the possesive versions:
```
you  >> your
them >> their
me   >> my
```

If using nouns also use the possessive thingy `'s`:
```
car  >> car's
John >> John's
```

With that said, let's apply it to the bad examples earlier:
```
[/kisses your lips]
[/ignites John's pants]
[/kills Maria's pet]
```

## Modifiers `{modifiers}`
Optional.

Anything that can enhance `<action> <target> {target-specific}`. There's no strict syntax to follow here, honestly.

Examples:
```
[/kisses your lips tenderly]
[/ignites John's pants with a passion]
[/kills Maria's pet aggressively]
[/fucks your mom whilst playing Fortnite in XBox One]
```

## Decorative String `{; <decor-string>}`
Optional.

Everything after the `;` would be identified as decorrative.

It is required to **only contain one word and must be captitalized**.

If your string contains one word, it must be broken down to one and must be placed on other RP lines.

In the following example, I will be using `I love you` as my decor string and using 3 random RP strings:

```
[/snorts cocaine; I]
[/shits my pants; LOVE]
[/licks your face passionately; YOU]
```

It is recommended to force your decor strings to start at the same column:

```
[/hugs you  ; I]
[/kisses you; LOVE]
[/fucks you ; YOU]
```
