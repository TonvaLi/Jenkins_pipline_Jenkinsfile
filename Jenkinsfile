node("tester_tt"){
    stage("one"){
        echo "start one"
        if(env.BRANCH_NAME == 'msater'){
            echo "I only execute on the master branch"
        }else{
            echo "lexecute anywhere"
        }
        sleep 1
    }
    stage("two"){
        echo "start two"
        sleep 1
    }
    stage("three"){
        echo "start three"
        sleep 2
    }
}
