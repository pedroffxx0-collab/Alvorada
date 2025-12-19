-- Alvorada Hub (script básico)

repeat task.wait() until game:IsLoaded()

local AlvoradaHub = {}

function AlvoradaHub.Start()
    game.StarterGui:SetCore("SendNotification", {
        Title = "Alvorada Hub";
        Text = "Script iniciado com sucesso!";
        Duration = 5;
    })

    print("Alvorada Hub iniciado")
end

-- inicia o hub
AlvoradaHub.Start()# Alvorada
Script blox fruits 
