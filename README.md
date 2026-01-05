# BSE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Breast Self Examination</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #fff0f6;
            color: #333;
            margin: 0;
            padding: 0 15px;
        }
        a { text-decoration: none; color: #d63384; }
        ul { list-style-type: none; padding: 0; }
        ul li { margin: 8px 0; }
        h1, h2, h3 { color: #d63384; }
        h1 { text-align: center; margin-top: 20px; }
        .section {
            background-color: #ffe6f0;
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 25px;
            box-shadow: 0 3px 8px rgba(0,0,0,0.1);
        }
        /* Quiz */
        .question { margin-bottom: 20px; }
        .question button {
            margin: 5px;
            padding: 8px 12px;
            font-size: 14px;
            cursor: pointer;
            border-radius: 8px;
            border: 1px solid #ff99c8;
            background-color: #ffd1e8;
            transition: 0.3s;
        }
        .question button:hover { background-color: #ff99c8; color: white; }
        .emoji { font-size: 24px; margin-left: 10px; }
        /* Open Forum */
        #OpenForum {
            padding: 25px;
            border-radius: 12px;
            max-width: 700px;
            margin: 30px auto;
            background: linear-gradient(145deg, #ffe0f0, #ffd1e8);
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        #OpenForum textarea {
            width: 100%;
            padding: 12px;
            border-radius: 8px;
            border: 1px solid #ff99c8;
            font-size: 14px;
            resize: none;
        }
        #OpenForum button {
            margin-top: 12px;
            padding: 10px 20px;
            cursor: pointer;
            border: none;
            border-radius: 8px;
            background-color: #ff66a3;
            color: white;
            font-weight: bold;
            font-size: 14px;
            transition: 0.3s;
        }
        #OpenForum button:hover { background-color: #d63384; }
        /* Facebook-style comments */
        .comment {
            background: #ffe6f0;
            padding: 10px 15px;
            border-radius: 12px;
            margin-bottom: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            color: #330033;
        }
        .comment-header {
            display: flex;
            justify-content: space-between;
            font-size: 14px;
            margin-bottom: 5px;
        }
        .comment-header .username { font-weight: bold; }
        .comment-header .timestamp { font-style: italic; color: #555; }
        .comment-actions {
            margin-top: 5px;
        }
        .comment-actions button {
            background-color: #ffd1e8;
            border: none;
            border-radius: 6px;
            padding: 4px 8px;
            margin-right: 5px;
            cursor: pointer;
            font-size: 12px;
        }
        .comment-actions button:hover { background-color: #ff99c8; color: white; }
        .reply {
            margin-left: 15px;
            background: #fff0f6;
            padding: 5px 10px;
            border-radius: 10px;
            margin-top: 5px;
            font-size: 14px;
        }

        #commentsSection { max-height: 300px; overflow-y: auto; }
    </style>
</head>
<body>

<header style="background-color:#ffd1e8; padding:15px 20px; display:flex; align-items:center; border-bottom: 3px solid #d63384; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h1 style="color:#d63384; font-size:28px; margin:0;">Breast Self Examination</h1>
</header>

<p><strong>Introduction</strong></p>
<ul>
    <li><a href="#BreastSelfExamination">Breast Self Examination</a></li>
    <li><a href="#DidYouKnow">Did You Know</a></li>
    <li><a href="#NormalBreastChanges">Normal Breast Changes</a></li>
    <li><a href="#QuizSection">Show me What You've Learned</a></li>
    <li><a href="#OpenForum">Open Forum</a></li>
</ul>

<!-- BSE Video -->
<div id="BreastSelfExamination" class="section">
    <h1>Breast Self Examination</h1>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/gsyha_CeetM" frameborder="0" allowfullscreen></iframe>
</div>

<!-- Did You Know -->
<div id="DidYouKnow" class="section">
    <h2>Did You Know?</h2>
    <p><strong>Breast self-examination helps women become familiar with the normal appearance and feel of their breasts.</strong><br>
    <small>— WHO</small></p>
    <p>Growing up means your body is <strong>changing</strong>—and that's normal. BSE is about awareness, not fear. It helps you notice changes early and take responsibility for your health. Self-care is empowering!</p>
</div>

<!-- Normal Breast Changes -->
<div id="NormalBreastChanges" class="section">
    <h2>Normal Breast Changes</h2>
    <img src="https://i.pinimg.com/1200x/a7/24/f9/a724f92123c624e99333853778fc489b.jpg" alt="BSE Illustration" style="display:block; margin:15px auto; border-radius:8px; max-width:100%;">
    <p style="text-align:center; font-style:italic; color:#555;">Illustration showing the steps for proper breast self-examination.</p>
</div>

<!-- Quiz -->
<div id="QuizSection" class="section">
    <h2>Quick Quiz</h2>
    <div class="question" data-answer="b">
        <p>1. Which month is Breast Cancer Awareness Month?</p>
        <button>a) June</button>
        <button>b) October</button>
        <button>c) December</button>
        <span class="emoji"></span>
    </div>
    <div class="question" data-answer="a">
        <p>2. How often should BSE be performed?</p>
        <button>a) Monthly</button>
        <button>b) Weekly</button>
        <button>c) Yearly</button>
        <span class="emoji"></span>
    </div>
    <div class="question" data-answer="c">
        <p>3. What is the main purpose of BSE?</p>
        <button>a) Cure breast cancer</button>
        <button>b) Replace doctor visits</button>
        <button>c) Early detection and awareness</button>
        <span class="emoji"></span>
    </div>
    <div class="question" data-answer="b">
        <p>4. Which part of the breast should be examined?</p>
        <button>a) Only nipples</button>
        <button>b) Entire breast including armpit</button>
        <button>c) Only upper part</button>
        <span class="emoji"></span>
    </div>
    <div class="question" data-answer="a">
        <p>5. BSE helps you notice changes in your breast <em>early</em>?</p>
        <button>a) True</button>
        <button>b) False</button>
        <span class="emoji"></span>
    </div>
</div>

<!-- Open Forum -->
<div id="OpenForum">
    <h2>💖 Open Forum</h2>
    <p style="text-align:center; color:#900c3f;">Share your thoughts or questions about breast health. Be supportive and kind!</p>
    <textarea id="commentInput" rows="4" placeholder="Write your comment here..."></textarea><br>
    <button id="submitComment">Submit</button>
    <h3 style="margin-top:20px; color:#d63384;">Comments:</h3>
    <div id="commentsSection"></div>
</div>

<script>
    // Quiz
    const questions = document.querySelectorAll('.question');
    questions.forEach(q => {
        const buttons = q.querySelectorAll('button');
        buttons.forEach(btn => {
            btn.addEventListener('click', () => {
                const emoji = q.querySelector('.emoji');
                const correctAnswer = q.dataset.answer;
                if(btn.textContent.startsWith(correctAnswer)){
                    emoji.textContent = '✅';
                } else {
                    emoji.textContent = '❌';
                }
            });
        });
    });

    // Open Forum with localStorage
    const submitButton = document.getElementById('submitComment');
    const commentInput = document.getElementById('commentInput');
    const commentsSection = document.getElementById('commentsSection');

    let comments = JSON.parse(localStorage.getItem('bseComments')) || [];

    function renderComments() {
        commentsSection.innerHTML = '';
        comments.forEach((c, index) => {
            const commentDiv = document.createElement('div');
            commentDiv.className = "comment";
            commentDiv.innerHTML = `
                <div class="comment-header">
                    <span class="username">${c.username}</span>
                    <span class="timestamp">${c.time}</span>
                </div>
                <p>${c.text}</p>
                <div class="comment-actions">
                    <button class="like-btn" data-count="${c.likes}">👍 Like (${c.likes})</button>
                    <button class="reply-btn">Reply</button>
                    <div class="replies"></div>
                </div>
            `;

            // Replies
            const repliesContainer = commentDiv.querySelector('.replies');
            if(c.replies){
                c.replies.forEach(r => {
                    const replyDiv = document.createElement('div');
                    replyDiv.className = 'reply';
                    replyDiv.textContent = r;
                    repliesContainer.appendChild(replyDiv);
                });
            }

            // Like button
            const likeBtn = commentDiv.querySelector('.like-btn');
            likeBtn.addEventListener('click', () => {
                c.likes++;
                saveComments();
                renderComments();
            });

            // Reply button
            const replyBtn = commentDiv.querySelector('.reply-btn');
            replyBtn.addEventListener('click', () => {
                const replyText = prompt('Write your reply:');
                if(replyText){
                    c.replies.push(replyText);
                    saveComments();
                    renderComments();
                }
            });

            commentsSection.appendChild(commentDiv);
        });
    }

    function saveComments(){
        localStorage.setItem('bseComments', JSON.stringify(comments));
    }

    submitButton.addEventListener('click', () => {
        const commentText = commentInput.value.trim();
        if(commentText){
            const newComment = {
                username: 'User',
                text: commentText,
                time: new Date().toLocaleString(),
                likes: 0,
                replies: []
            };
            comments.unshift(newComment); // newest on top
            saveComments();
            renderComments();
            commentInput.value = '';
        } else {
            alert('Please write a comment before submitting.');
        }
    });

    commentInput.addEventListener('keypress', function(e){
        if(e.key === 'Enter' && !e.shiftKey){
            e.preventDefault();
            submitButton.click();
        }
    });

    renderComments();
</script>

</body>
</html>
