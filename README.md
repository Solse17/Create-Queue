# Create-Queue
Private q As New Queue
    Sub CreateMyQueue(
                     strPathq As String
                     )
        q.Enqueue(“gate ”)
        q.Enqueue(“toilet”)
        q.Enqueue(“shop”)
        q.Enqueue(“food”)
        q.Enqueue(“info”)
        q.Enqueue(“gate 1”)
        q.Enqueue(“gate 2”)
        q.Enqueue(“gate 3”)
        q.Enqueue(“gate 4”)
        q.Enqueue(“gate 5”)
        q.Enqueue(“gate 6”)
        q.Enqueue(“gate 7”)
        q.Enqueue(“gate 8”)
        q.Enqueue(“gate 9”)
        q.Enqueue(“gate 10”)
        q.Enqueue(“gate 11”)
        MsgBox(q.Peek().ToString())
        
    End Sub
