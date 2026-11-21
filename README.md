<img width="1024" height="1024" alt="1000124944" src="https://github.com/user-attachments/assets/29ddcd10-473f-446f-a2c2-7ada011d79e4" />
┌──────────────────────────────────────────────────────────┐
│                 AlNoorApp (RTL + Theme)                  │
│   ┌──────────────┬──────────────┬────────────────────┐   │
│   │  HomeScreen  │CatalogScreen │  SavedQuotesScreen │   │
│   │  + SearchBar │+ Filter/Sort │  + Share/WhatsApp  │   │
│   └──────┬───────┴──────┬───────┴─────────┬──────────┘   │
│          │              │                 │              │
│   ┌──────▼──────────────▼─────────────────▼──────────┐   │
│   │                ShowroomViewModel                 │   │
│   │  StateFlow<ShowroomUiState> + SYP Formatter      │   │
│   └──────┬────────────────────────────────┬──────────┘   │
│          │                                │              │
│   ┌──────▼───────────────┐      ┌─────────▼──────────┐   │
│   │ShowroomCatalogRepo   │      │SavedSelectionStore │   │
│   │(16 Curated Products) │      │(DataStore Prefs)   │   │
│   └──────────────────────┘      └────────────────────┘   │
└──────────────────────────────────────────────────────────┘
                            │
                            ▼ (Release Packaging & Standalone Web)
┌──────────────────────────────────────────────────────────┐
│  Android APK / AAB Ready   +   Self-Contained HTML File  │
│  (Play-Compliant & Signed)     (Embedded Real Imagery)   │
└──────────────────────────────────────────────────────────┘
