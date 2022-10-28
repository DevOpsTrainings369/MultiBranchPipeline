properties([
    parameters([
        [$class: 'ChoiceParameter', 
            choiceType: 'PT_SINGLE_SELECT', 
            description: 'Select the Environemnt from the Dropdown List', 
            name: 'Env', 
            script: [
                $class: 'GroovyScript', 
                fallbackScript: [
                    classpath: [], 
                    sandbox: true, 
                    script: 
                        "return['Could not get The environemnts']"
                ], 
                script: [
                    classpath: [], 
                    sandbox: true, 
                    script: 
                        "return['dev','stage','prod']"
                ]
            ]
        ],
    ])
])

