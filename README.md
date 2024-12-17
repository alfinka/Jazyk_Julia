# 👩 Online kurzy Julia
Materiály k online kurzom Julia

## Čo je to Julia?
Julia je **moderný, vysokovýkonný programovací jazyk**, ktorý bol navrhnutý najmä pre **vedecké výpočty**, **analýzu údajov** a **numerické simuláci**e. Kombinuje výhody rýchlosti kompilovaných jazykov, ako sú C alebo Fortran, s jednoduchosťou dynamických jazykov, ako je Python. Julia podporuje prácu s maticami a vektorovými výpočtami, čo z nej robí populárny jazyk vo **výskume**, **strojovom učení** a **finančných analýzach**.

## Prečo sa Julia volá Julia?
Názov programovacieho jazyka Julia nevychádza zo špecifického technického významu, ale z jednoduchej voľby jeho autorov. Podľa zakladateľov jazyka, chceli pomenovanie, ktoré je krátke, pútavé, ľahko zapamätateľné a má pozitívny nádych. Názov "Julia" bol vybraný bez hlbokého príbehu za ním – zakladateľ Alan Edelman raz spomenul, že sa mu páčilo pomenovať jazyk Julia, a toto meno zostalo. Navyše, **názov nie je skratkou ani akronymom**, ale bol vybraný ako **ľudský**, **priateľský názov**, ktorý môže **evokovať prístupnosť**.

##  Ako vznikol jazyk Julia?
Jazyk Julia vznikol s cieľom spojiť výhody **rýchlosti nízkoúrovňových jazykov** ako **C** a **Fortran** s **jednoduchosťou**, **interaktivitou** a **flexibilitou** **jazykov** ako **Python**, **R** alebo **MATLAB**. Autori sa snažili vytvoriť jazyk, ktorý umožní vedeckým pracovníkom, inžinierom a vývojárom používať jeden jazyk pre všetko: rýchle prototypovanie, vysokovýkonné výpočty aj distribúciu produkčných aplikácií.

## Kto je autor jazyka Julia?
Julia bola vytvorená tímom 4 zakladateľov:
1. **Alan Edelman** – známy matematik a profesor na MIT, odborník na numerické výpočty.
1. Jeff Bezanson – softvérový inžinier a dizajnér programovacích jazykov.
1. Stefan Karpinski – odborník na dátové analýzy a vývoj softvéru.
1.  Viral B. Shah – expert na distribúciu a implementáciu výpočtových systémov.
Prvá verzia jazyka bola verejne predstavená vo februári 2012. Odvtedy si Julia získala širokú komunitu a stala sa populárnou najmä v oblasti numerických výpočtov, dátovej vedy a strojového učenia.

## Hlavné vlastnosti a výhody Julia
1. **Rýchlosť:** Julia je takmer rovnako rýchla ako jazyky C alebo Fortran vďaka využitiu JIT (Just-In-Time) kompilácie cez LLVM (Low-Level Virtual Machine).
1. **Jednoduchá syntax:** Syntax je prehľadná a pripomína jazyky ako Python alebo MATLAB, čo ju robí prístupnou aj pre začiatočníkov.
1. **Dynamické typovanie:** Podporuje dynamické typovanie, čo znamená, že nemusíte explicitne deklarovať dátové typy, ale môžete ich použiť, ak je to potrebné pre optimalizáciu.
1. **Podpora paralelizácie a distribuovaných výpočtov:** Julia je navrhnutá s dôrazom na paralelné spracovanie a dokáže efektívne využívať viacjadrové procesory alebo distribuované systémy.
1. **Bohatá knižnica balíčkov:** Má rozsiahly ekosystém balíčkov na rôzne účely, od strojového učenia (napr. Flux.jl) cez numerickú matematiku až po vizualizáciu dát.
1. **Interoperabilita:** Dokáže komunikovať s inými jazykmi, ako sú Python, R, C, Fortran či Java. To umožňuje využívať už existujúce knižnice a integráciu so staršími systémami.
1. **Podpora pre metaprogramovanie:** Umožňuje prácu s makrami a generovanie kódu počas behu programu, čo poskytuje vysokú flexibilitu pri tvorbe aplikácií.
1. **Otvorený zdrojový kód:** Julia je open-source a aktívne vyvíjaná komunitou, čo znamená, že je voľne dostupná na použitie a rozširovanie.


## 🛠️ Inštalácia Julia a integrácia s Jupyter Notebook v Anaconde

---

## ✅ **1. Inštalácia Julia**

1. **Stiahnite a nainštalujte Juliu** 💾:
   - Prejdite na [oficiálnu stránku Julii](https://julialang.org/downloads/).
   - Stiahnite si inštalačný súbor pre vašu platformu (Windows, macOS, Linux).
   - Spustite inštalačný program a nainštalujte Juliu.

2. **Pridajte cestu do premenných prostredia** (⚖️ pre Windows):
   - Pridajte cestu napr. `C:\Users\<vaše_meno>\AppData\Local\Julia-<verzia>` do **Path**.

---

## 🔢 **2. Inštalácia IJulia**

1. **Spustite Juliu**:
   - Otvorte aplikáciu **Julia REPL** (terminál Julii).

2. **Nainštalujte balík IJulia** 🛠:
   ```julia
   using Pkg
   Pkg.add("IJulia")
   ```

3. **Overte inštaláciu IJulia** 🔄:
   ```julia
   using IJulia
   notebook()
   ```
   - Tento príkaz spustí Jupyter Notebook, ak je nainštalovaný.

---

## 📚 **3. Inštalácia Jupyter Notebook cez Anacondu**

1. **Inštalácia Anacondy** 📂:
   - Stiahnite si [Anacondu](https://www.anaconda.com/) a nainštalujte ju.

2. **Overte inštaláciu Jupyter Notebook** 🔀:
   ```bash
   conda list jupyter
   ```
   - Ak Jupyter chýba, nainštalujte ho:
     ```bash
     conda install -c conda-forge notebook
     ```

---

## 🛢 **4. Pridanie kernelu Julii do Jupyter Notebooku**

1. **Kernel sa pridá automaticky po IJulia inštalácii** 🌐.

2. **Spustite Jupyter Notebook** 🔧:
   ```bash
   jupyter notebook
   ```

3. **Vyberte kernel Julia** ✏️:
   - Kliknite na **New** ➞ **Julia 1.x.x** v Jupyter Notebooku.

---

## 📊 **5. Testovanie Julii v Jupyter Notebooku**

1. **Spustite jednoduchý príklad** 👍:
   ```julia
   println("Ahoj, Julia v Jupyter Notebooku!")
   ```

2. **Hotovo!** 🎉 Teraz môžete používať Juliu v Jupyter Notebookoch.

---


## 🚀 Praktické príklady v jazyku Julia

## 1️⃣ 🧮 Základné aritmetické operácie
```julia
# Sčítanie, odčítanie, násobenie a delenie s podmienkami
a = 10
b = 5
println("Súčet: ", a + b)
println("Rozdiel: ", a - b)
println("Násobok: ", a * b)
println("Podiel: ", a / b)

if b != 0
    println("Delenie: ", a / b)
else
    println("Delenie nie je možné, deliteľ je nulový.")
end
```

## 2️⃣ 🔢 Práca s poľami (arrays)
```julia
# Operácie s poľami - štatistika a transformácia
pole = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
println("Maximálny prvok: ", maximum(pole))
println("Medián: ", median(pole))

filtrované_pole = filter(x -> x % 2 == 0, pole)
transformované_pole = map(x -> x^2, pole)
println("Párne čísla: ", filtrované_pole)
println("Transformované pole (x^2): ", transformované_pole)
```

## 3️⃣ 📊 Pokročilé plotovanie
```julia
using Plots
x = 1:0.1:10
y1 = x .^ 2
y2 = sin.(x)

p1 = plot(x, y1, label="y = x^2", xlabel="x", ylabel="y", title="Parabolický graf")
p2 = plot(x, y2, label="y = sin(x)", xlabel="x", ylabel="y", title="Sinusový graf")
plot(p1, p2, layout=(2, 1))
```

## 4️⃣ 🔄 Podmienky a cykly
```julia
function rozhodnutie(a, b)
    if a > b
        return "$a je väčšie ako $b"
    elseif a == b
        return "$a je rovné $b"
    else
        return "$a je menšie ako $b"
    end
end

for i in 1:5
    println("Pre i = $i: ", rozhodnutie(i, 3))
end
```

## 5️⃣ 🧩 Funkcie s predvolenými hodnotami
```julia
function pozdrav(meno, pozdrav_kompletne=true)
    if pozdrav_kompletne
        return "Ahoj, $meno! Vitaj!"
    else
        return "Ahoj, $meno!"
    end
end

println(pozdrav("Júlia", false))
```

## 6️⃣ 📏 Pokročilé matematické operácie
```julia
using Optim

f(x) = (x - 3)^2 + 1
result = optimize(f, 0.0, 5.0)
println("Minimum funkcie je v bode: ", result.minimizer)
```

## 7️⃣ 🔢 Operácie s maticami
```julia
using LinearAlgebra

matica = [1 2 3; 4 5 6; 7 8 9]
println("Inverzná matica:
", inv(matica))
```

## 8️⃣ ⚡ Paralelný výpočet
```julia
using SharedArrays

function paralelný_sumar(pole)
    suma = SharedVector{Int}(1)
    @distributed for i in 1:length(pole)
        atomic_add!(suma, pole[i])
    end
    return suma[1]
end

pole = [1, 2, 3, 4, 5]
println("Paralelný súčet: ", paralelný_sumar(pole))
```

