# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API with no auth and no CORS from the following list. It _should not_ be one that you've already seen or worked on in class.
   - [Public APIs](https://github.com/public-apis/public-apis)
1. Choose an API not covered in your readings, class, or other assignments. The API should be new to you.
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.
1. Take the time to read back the work, and edit what you've written so that your answers are clear and anyone reading it can easily understand what you've written.

## Instructions

Do your best to answer the questions with specific details. Writing about code clearly and thoroughly is a critical skill to practice.

- Which one did you choose? Provide the name and base URL.

> https://www.dnd5eapi.co

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to show all the available information for dnd including but not limited to items, spells, monsters, etc.

- What is the URL of the documentation?

> https://www.dnd5eapi.co/docs

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://www.dnd5eapi.co/api/monsters/vampire-vampire

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "index": "vampire-vampire",
    "name": "Vampire, Vampire Form",
    "size": "Medium",
    "type": "undead",
    "subtype": "shapechanger",
    "alignment": "lawful evil",
    "armor_class": [
        {
            "type": "natural",
            "value": 16
        }
    ],
    "hit_points": 144,
    "hit_dice": "17d8",
    "hit_points_roll": "17d8+68",
    "speed": {
        "walk": "30 ft."
    },
    "forms": [
        {
            "index": "vampire-bat",
            "name": "Vampire, Bat Form",
            "url": "/api/monsters/vampire-bat"
        },
        {
            "index": "vampire-mist",
            "name": "Vampire, Mist Form",
            "url": "/api/monsters/vampire-mist"
        }
    ],
    "strength": 18,
    "dexterity": 18,
    "constitution": 18,
    "intelligence": 17,
    "wisdom": 15,
    "charisma": 18,
    "proficiencies": [
        {
            "value": 9,
            "proficiency": {
                "index": "saving-throw-dex",
                "name": "Saving Throw: DEX",
                "url": "/api/proficiencies/saving-throw-dex"
            }
        },
        {
            "value": 7,
            "proficiency": {
                "index": "saving-throw-wis",
                "name": "Saving Throw: WIS",
                "url": "/api/proficiencies/saving-throw-wis"
            }
        },
        {
            "value": 9,
            "proficiency": {
                "index": "saving-throw-cha",
                "name": "Saving Throw: CHA",
                "url": "/api/proficiencies/saving-throw-cha"
            }
        },
        {
            "value": 7,
            "proficiency": {
                "index": "skill-perception",
                "name": "Skill: Perception",
                "url": "/api/proficiencies/skill-perception"
            }
        },
        {
            "value": 9,
            "proficiency": {
                "index": "skill-stealth",
                "name": "Skill: Stealth",
                "url": "/api/proficiencies/skill-stealth"
            }
        }
    ],
    "damage_vulnerabilities": [],
    "damage_resistances": [
        "necrotic",
        "bludgeoning, piercing, and slashing from nonmagical weapons"
    ],
    "damage_immunities": [],
    "condition_immunities": [],
    "senses": {
        "darkvision": "120 ft.",
        "passive_perception": 17
    },
    "languages": "the languages it knew in life",
    "challenge_rating": 13,
    "proficiency_bonus": 5,
    "xp": 10000,
    "special_abilities": [
        {
            "name": "Shapechanger",
            "desc": "If the vampire isn't in sun light or running water, it can use its action to polymorph into a Tiny bat or a Medium cloud of mist, or back into its true form.\nWhile in bat form, the vampire can't speak, its walking speed is 5 feet, and it has a flying speed of 30 feet. Its statistics, other than its size and speed, are unchanged. Anything it is wearing transforms with it, but nothing it is carrying does. It reverts to its true form if it dies.\nWhile in mist form, the vampire can't take any actions, speak, or manipulate objects. It is weightless, has a flying speed of 20 feet, can hover, and can enter a hostile creature's space and stop there. In addition, if air can pass through a space, the mist can do so without squeezing, and it can't pass through water. It has advantage on Strength, Dexterity, and Constitution saving throws, and it is immune to all nonmagical damage, except the damage it takes from sunlight."
        },
        {
            "name": "Legendary Resistance",
            "desc": "If the vampire fails a saving throw, it can choose to succeed instead.",
            "usage": {
                "type": "per day",
                "times": 3,
                "rest_types": []
            }
        },
        {
            "name": "Misty Escape",
            "desc": "When it drops to 0 hit points outside its resting place, the vampire transforms into a cloud of mist (as in the Shapechanger trait) instead of falling unconscious, provided that it isn't in sunlight or running water. If it can't transform, it is destroyed.\nWhile it has 0 hit points in mist form, it can't revert to its vampire form, and it must reach its resting place within 2 hours or be destroyed. Once in its resting place, it reverts to its vampire form. It is then paralyzed until it regains at least 1 hit point. After spending 1 hour in its resting place with 0 hit points, it regains 1 hit point."
        },
        {
            "name": "Regeneration",
            "desc": "The vampire regains 20 hit points at the start of its turn if it has at least 1 hit point and isn't in sunlight or running water. If the vampire takes radiant damage or damage from holy water, this trait doesn't function at the start of the vampire's next turn."
        },
        {
            "name": "Spider Climb",
            "desc": "The vampire can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
        },
        {
            "name": "Vampire Weaknesses",
            "desc": "The vampire has the following flaws:\nForbiddance. The vampire can't enter a residence without an invitation from one of the occupants.\nHarmed by Running Water. The vampire takes 20 acid damage if it ends its turn in running water.\nStake to the Heart. If a piercing weapon made of wood is driven into the vampire's heart while the vampire is incapacitated in its resting place, the vampire is paralyzed until the stake is removed.\nSunlight Hypersensitivity. The vampire takes 20 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks."
        }
    ],
    "actions": [
        {
            "name": "Multiattack",
            "multiattack_type": "action_options",
            "desc": "The vampire makes two attacks, only one of which can be a bite attack.",
            "action_options": {
                "choose": 1,
                "type": "action",
                "from": {
                    "option_set_type": "options_array",
                    "options": [
                        {
                            "option_type": "multiple",
                            "items": [
                                {
                                    "option_type": "action",
                                    "action_name": "Unarmed Strike (Vampire Form Only)",
                                    "count": 1,
                                    "type": "melee"
                                },
                                {
                                    "option_type": "action",
                                    "action_name": "Bite (Bat or Vampire Form Only)",
                                    "count": 1,
                                    "type": "melee"
                                }
                            ]
                        },
                        {
                            "option_type": "action",
                            "action_name": "Unarmed Strike (Vampire Form Only)",
                            "count": 2,
                            "type": "melee"
                        }
                    ]
                }
            },
            "actions": []
        },
        {
            "name": "Unarmed Strike",
            "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. Hit: 8 (1d8 + 4) bludgeoning damage. Instead of dealing damage, the vampire can grapple the target (escape DC 18).",
            "attack_bonus": 9,
            "damage": [
                {
                    "damage_type": {
                        "index": "bludgeoning",
                        "name": "Bludgeoning",
                        "url": "/api/damage-types/bludgeoning"
                    },
                    "damage_dice": "1d8+4"
                }
            ],
            "actions": []
        },
        {
            "name": "Bite",
            "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one willing creature, or a creature that is grappled by the vampire, incapacitated, or restrained. Hit: 7 (1d6 + 4) piercing damage plus 10 (3d6) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0. A humanoid slain in this way and then buried in the ground rises the following night as a vampire spawn under the vampire's control.",
            "attack_bonus": 9,
            "damage": [
                {
                    "damage_type": {
                        "index": "piercing",
                        "name": "Piercing",
                        "url": "/api/damage-types/piercing"
                    },
                    "damage_dice": "1d6+4"
                },
                {
                    "damage_type": {
                        "index": "necrotic",
                        "name": "Necrotic",
                        "url": "/api/damage-types/necrotic"
                    },
                    "damage_dice": "3d6"
                }
            ],
            "actions": []
        },
        {
            "name": "Charm",
            "desc": "The vampire targets one humanoid it can see within 30 ft. of it. If the target can see the vampire, the target must succeed on a DC 17 Wisdom saving throw against this magic or be charmed by the vampire. The charmed target regards the vampire as a trusted friend to be heeded and protected. Although the target isn't under the vampire's control, it takes the vampire's requests or actions in the most favorable way it can, and it is a willing target for the vampire's bit attack.\nEach time the vampire or the vampire's companions do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until the vampire is destroyed, is on a different plane of existence than the target, or takes a bonus action to end the effect.",
            "dc": {
                "dc_type": {
                    "index": "wis",
                    "name": "WIS",
                    "url": "/api/ability-scores/wis"
                },
                "dc_value": 17,
                "success_type": "none"
            },
            "actions": []
        },
        {
            "name": "Children of the Night",
            "desc": "The vampire magically calls 2d4 swarms of bats or rats, provided that the sun isn't up. While outdoors, the vampire can call 3d6 wolves instead. The called creatures arrive in 1d4 rounds, acting as allies of the vampire and obeying its spoken commands. The beasts remain for 1 hour, until the vampire dies, or until the vampire dismisses them as a bonus action.",
            "usage": {
                "type": "per day",
                "times": 1
            },
            "actions": []
        }
    ],
    "legendary_actions": [
        {
            "name": "Move",
            "desc": "The vampire moves up to its speed without provoking opportunity attacks.",
            "attack_bonus": 0
        },
        {
            "name": "Unarmed Strike",
            "desc": "The vampire makes one unarmed strike.",
            "attack_bonus": 0
        },
        {
            "name": "Bite (Costs 2 Actions)",
            "desc": "The vampire makes one bite attack.",
            "attack_bonus": 0
        }
    ],
    "url": "/api/monsters/vampire-vampire"
}

```

- What status code did you get back from your request? Why did you receive this status code?

> I recived a 200 status code because the request succeeded and gave me the expected response.

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`: 8054

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes a monster, particularly a vampires abilites, damage type, what dice is needed to roll it's damage, its move set, a description of it, weaknesses, etc.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that allows dnd players to easily look up information on monsters, what dice to roll for damage, or what the specific monster is. The second way would be to use the information on a web app that allows you to simulate battles between two different monsters.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was useful in showing you examples on how to use the endpoints and its query params. A specific example is on the api website you can get an example on what it would look like if you used the monster's challenge rating query param. The challenge rating is how difficult the monster is to defeat. In the example above you can see the vampire is at challenge rating 13, while a ghoul is challenge rating 1.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation was very thorough and didnt lack any information.

- Did the quality of the documentation impact your decision to use it?

> Yes because it looked organized and clearly layed out.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> No because this API was straight forward and the well designed documentation made it easy to work with. 

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is when a client sends a request to a server in one of four specific ways: create, read, update, delete, or CRUD. The server then processes the request, generates a response, and sends it back to the client. The client then receives and processes the response, usually visually represented in some way.

- In your own words, describe what an API is.

> An API is a set of rules and tools that allows different software applications to communicate with each other. It defines the methods and data formats that applications can use to request and exchange information.  

- In your own words, describe the purpose of Postman.

> Postman is an application that allows developers a GUI to send and recieve http requests, as well as, testing and debugging. 