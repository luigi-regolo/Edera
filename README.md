# Edera

Tema **Light + Graphite Dark** per Home Assistant, con palette semantica, superfici pulite e colori pensati per rendere gli stati immediatamente leggibili.

> **Sicurezza e privacy**  
> Edera è esclusivamente un tema grafico. Non accede a dispositivi, automazioni, credenziali, token, indirizzi IP o dati personali e non modifica le logiche della tua installazione Home Assistant.

## Anteprima

| Graphite Dark | Light |
| --- | --- |
| ![Edera Graphite Dark](images/edera-dark.png) | ![Edera Light](images/edera-light.png) |

## In breve

- modalità **Light** e **Graphite Dark**
- colori semantici per distinguere rapidamente gli stati
- luci **Warm Ivory / Brass**
- dispositivi attivi **Emerald**
- media **Petrol**
- colori dedicati per clima, warning e allarmi
- palette coordinata per i grafici
- font di sistema, senza font esterni
- compatibile con le card native di Home Assistant
- nessuna dipendenza custom obbligatoria

## Installazione

### HACS

Aggiungi `https://github.com/luigi-regolo/Edera` agli **Archivi digitali personalizzati** di HACS come tipo **Tema**, quindi installa Edera.

### Manuale

Copia `themes/edera.yaml` in:

```text
/config/themes/
```

Assicurati che in `configuration.yaml` sia presente:

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

Poi ricarica i temi da Home Assistant.

## Logica dei colori

| Categoria | Colore |
| --- | --- |
| Dispositivo attivo | Emerald |
| Luce accesa | Warm Ivory / Brass |
| Media | Petrol |
| Riscaldamento | Terracotta |
| Raffrescamento | Soft Blue |
| Warning | Amber |
| Allarme / problema critico | Alert Red |
| Spento / inattivo | Neutral |

## Componenti opzionali

Edera funziona **senza dipendenze custom**.

Bubble Card, Mushroom e card-mod possono essere utilizzati per personalizzazioni aggiuntive, ma non sono necessari per il tema base e possono richiedere manutenzione dopo aggiornamenti di Home Assistant.

## Licenza

Edera può essere utilizzato gratuitamente per uso personale e non commerciale. Vendita, rivendita e distribuzione commerciale non sono consentite senza autorizzazione.

Consulta [LICENSE](LICENSE) per i termini completi.

## Versione

**Edera 1.0.0**
