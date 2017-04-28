---
layout: post
title:  "Afstudeerwerk: Edit validation"
date:   2017-04-26 20:03:00 +0100
categories: jekyll update
---
We hadden een issue gemaakt, een tijdje geleden, dat er nog geen validation (client- noch serverside) was bij de edit functionaliteit. Los vergeten. Dat was vandaag aan de beurt. Heel wat liggen prutsen met de redirect, als de validatie faalt. Ten slotte beslist dat het niet performant is een hele neiuwe VM te maken voor die redirect, en er wordt gewoon geredirect naar een action, met de 'oude' content.