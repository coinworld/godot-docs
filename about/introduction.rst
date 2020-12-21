.. _doc_about_intro:

Introduction
============

::

    func _ready():
        $Label.text = "Hello world!"

자유이며 오픈소스이며 커뮤니티 주도로 개발되는 2D와 3D 게임 엔진인 Godot Engine의 공식 문서에 오신 것을 환영합니다.
이 말 속에는, 이 게임 엔진이 모든 플랫폼에서 작동하고, 모든 종류의 게임을 개발할 수 있고, 강력하면서도, 유저 친화적인 툴이면서도,
사용에 있어서 아무 제한이 없다는 것을 말합니다.

이 페이지는 엔진과 이 문서의 내용에 대해 포괄적인 이해를 다룹니다. 그래서 이 문서를 읽고 나시면 초보자라면
어디서 시작해야 하는지, 아니면 이미 찾는 내용이 있었다면 그 내용이 어디에 있는지 알 수 있을 겁니다.

시작하기 전에
----------------

:ref:`Tutorials and resources <doc_community_tutorials>` 페이지는 커뮤니티가 만든 비디오 튜토리얼들이 있습니다.
만약 글보다 영상을 선호하신다면 둘러보실 가치가 있을지도 모르겠네요.

튜토리얼을 읽다가 문제가 발생하거나, 프로젝트에 문제가 생기셨다면 다양한 :ref:`Community channels <doc_community_channels>`을
통해서 도움을 청할 수 있습니다. Godot Discord 커뮤니티, Q&A와 IRC가 대표적입니다.

Godot Engine에 대해
------------------

게임 엔진은 복잡한 도구입니다. 따라서 Godot을 단 몇 단어로만 표현하기에는 무리가 있죠.
여기 간단한 개요가 있습니다. 만약 Godot Engine에 대해서 간단하게 소개할 필요가 있다면 그냥 갖다가 쓰셔도 무방합니다.

    Godot Engine은 여러 기능을 포함한, 2D와 3D 게임을 한 인터페이스에서 만들 수 있는 크로스
    플랫폼 게임 엔진입니다. 이미 이 엔진에서 주로 쓰이는 툴들의 대부분을 제공하므로, 굳이 쓸데없이
    다른 툴들을 쓰려고 하지 않고 그냥 게임 개발에만 집중할 수 있습니다. 게임은 단지 한번의 클릭만으로
    주요 데스크탑 플랫폼 (Linux, macOS, Windows), 모바일 (Android, iOS), 그리고 웹 기반 (HTML5)로
    내보낼 수 있습니다.
    
    Godot은 관대한 MIT 라이선스 하에 완전히 자유이며 오픈소스입니다. 아무 조건도 없고,
    아무 로열티도 없습니다. 유저가 만든 게임은 그대로 유저들의 것입니다. Godot의 개발은 완전히
    독립적이고 커뮤니티 주도 하에 이루어집니다. 따라서 유저들이 게임 엔진에 원하는 것이 있으면 그걸
    구현하는 것도 가능합니다. `Software Freedom Conservancy <https://sfconservancy.org>`_ not-for-profit이
    이를 지원합니다.

이 엔진에 대해 더 알고 싶으시다면, 이 문서를 더 읽으시면 됩니다.
:ref:`Step by step <toc-learn-step_by_step>` 부분을 추천합니다.

About the documentation
-----------------------

This documentation is continuously written, corrected, edited, and revamped by
members of the Godot Engine community. It is edited via text files in the
`reStructuredText <http://www.sphinx-doc.org/en/stable/rest.html>`_ markup
language and then compiled into a static website/offline document using the
open source `Sphinx <http://www.sphinx-doc.org>`_ and `ReadTheDocs
<https://readthedocs.org/>`_ tools.

.. note:: You can contribute to Godot's documentation by opening issue tickets
          or sending patches via pull requests on its GitHub
          `source repository <https://github.com/godotengine/godot-docs>`_, or
          translating it into your language on `Hosted Weblate
          <https://hosted.weblate.org/projects/godot-engine/godot-docs/>`_.

All the contents are under the permissive Creative Commons Attribution 3.0
(`CC-BY 3.0 <https://creativecommons.org/licenses/by/3.0/>`_) license, with
attribution to "Juan Linietsky, Ariel Manzur and the Godot Engine community".

Organization of the documentation
---------------------------------

This documentation is organized in five sections with an impressively
unbalanced distribution of contents – but the way it is split up should be
relatively intuitive:

- The :ref:`sec-general` section contains this introduction as well as
  information about the engine, its history, its licensing, authors, etc. It
  also contains the :ref:`doc_faq`.
- The :ref:`sec-learn` section is the *raison d'être* of this
  documentation, as it contains all the necessary information on using the
  engine to make games. It starts with the :ref:`Step by step
  <toc-learn-step_by_step>` tutorial which should be the entry point for all
  new users.
- The :ref:`sec-tutorials` section can be read as needed,
  in any order. It contains feature-specific tutorials and documentation.
- The :ref:`sec-devel` section is intended for advanced users and contributors
  to the engine development, with information on compiling the engine,
  developing C++ modules or editor plugins.
- The :ref:`sec-community` section gives information related to contributing to
  engine development and the life of its community, e.g. how to report bugs,
  help with the documentation, etc. It also points to various community channels
  like IRC and Discord and contains a list of recommended third-party tutorials
  outside of this documentation.
- Finally, the :ref:`sec-class-ref` is the documentation of the Godot API,
  which is also available directly within the engine's script editor. It is
  generated automatically from a file in the main source repository, therefore
  the generated files of the documentation are not meant to be modified. See
  :ref:`doc_updating_the_class_reference` for details.

In addition to this documentation you may also want to take a look at the
various `Godot demo projects <https://github.com/godotengine/godot-demo-projects>`_.

Have fun reading and making games with Godot Engine!
