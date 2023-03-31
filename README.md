--- Open Source made by 03.s#6260
--- CREATOR 03.s#6260
--- this for car dealership tycoon


codes = {"Drifting","Season3","CriminalVan","Helicopter","Hey2023","7Quests","XmasIncoming","HyperDealer","Tstingray","FOXZIE","4Years"}
       

for _, v in pairs(codes) do
pcall(function() game:GetService("ReplicatedStorage").Remotes.Code:FireServer(v)    end)
end
