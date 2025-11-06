# ターミナル操作の補足

1.  **backend (Fast API)**

    以下のコマンドを順に実行

    ```bash
    cd backend
    ```
    ```bash
    python -m venv myenv
    ```
    ```bash
    myenv\Scripts\activate
    ```
    ```bash
    pip install -r requirements.txt
    ```
    ```bash
    uvicorn app:app --reload --port 8000
    ```

2.  **frontend (Next.js)**

    以下のコマンドを順に実行

    ```bash
    cd frontend
    ```
    ```bash
    npm install
    ```
    ```bash
    npm run dev
    ```

---

# ブラウザの開き方の補足

ブラウザのアドレスに `/customers` の追加が必要

**http://localhost:3000/customers**
gi
として更新すると演習1の画面が開く

