<Type Name="TileBinding" FullName="Microsoft.Azure.Mobile.Server.TileBinding">
  <TypeSignature Language="C#" Value="public class TileBinding" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TileBinding extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.TileBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class TileBinding" />
  <TypeSignature Language="F#" Value="type TileBinding = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            このクラスを表します、<c>バインディング</c>Windows Notification タイルの要素を参照してください<c>http://msdn.microsoft.com/en-us/library/windows/apps/hh761491.aspx</c>詳細についてはします。
            このクラスは、の一部として使用するものでは、<see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TileBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TileBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TileBinding (params Microsoft.Azure.Mobile.Server.TileImage[] images);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Mobile.Server.TileImage[] images) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TileBinding.#ctor(Microsoft.Azure.Mobile.Server.TileImage[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray images As TileImage())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.TileBinding : Microsoft.Azure.Mobile.Server.TileImage[] -&gt; Microsoft.Azure.Mobile.Server.TileBinding" Usage="new Microsoft.Azure.Mobile.Server.TileBinding images" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="images" Type="Microsoft.Azure.Mobile.Server.TileImage[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="images">初期の一連の<see cref="T:Microsoft.Azure.Mobile.Server.TileImage" />このタイルにします。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TileBinding (params Microsoft.Azure.Mobile.Server.TileText[] texts);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Mobile.Server.TileText[] texts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TileBinding.#ctor(Microsoft.Azure.Mobile.Server.TileText[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray texts As TileText())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.TileBinding : Microsoft.Azure.Mobile.Server.TileText[] -&gt; Microsoft.Azure.Mobile.Server.TileBinding" Usage="new Microsoft.Azure.Mobile.Server.TileBinding texts" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="texts" Type="Microsoft.Azure.Mobile.Server.TileText[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="texts">初期の一連の<see cref="T:Microsoft.Azure.Mobile.Server.TileText" />このタイルにします。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TileBinding (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Mobile.Server.TileImage&gt; images, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Mobile.Server.TileText&gt; texts);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Mobile.Server.TileImage&gt; images, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Mobile.Server.TileText&gt; texts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TileBinding.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Azure.Mobile.Server.TileImage},System.Collections.Generic.IEnumerable{Microsoft.Azure.Mobile.Server.TileText})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (images As IEnumerable(Of TileImage), texts As IEnumerable(Of TileText))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.TileBinding : seq&lt;Microsoft.Azure.Mobile.Server.TileImage&gt; * seq&lt;Microsoft.Azure.Mobile.Server.TileText&gt; -&gt; Microsoft.Azure.Mobile.Server.TileBinding" Usage="new Microsoft.Azure.Mobile.Server.TileBinding (images, texts)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="images" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Mobile.Server.TileImage&gt;" />
        <Parameter Name="texts" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Mobile.Server.TileText&gt;" />
      </Parameters>
      <Docs>
        <param name="images">初期の一連の<see cref="T:Microsoft.Azure.Mobile.Server.TileImage" />このタイルにします。</param>
        <param name="texts">初期の一連の<see cref="T:Microsoft.Azure.Mobile.Server.TileText" />このタイルにします。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddImageQuery">
      <MemberSignature Language="C#" Value="public bool AddImageQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AddImageQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.AddImageQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property AddImageQuery As Boolean" />
      <MemberSignature Language="F#" Value="member this.AddImageQuery : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.AddImageQuery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(false)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("addImageQuery")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            イメージ タイル通知で指定された URI にクエリ文字列を追加するウィンドウを許可する場合は true に設定します。 サーバー イメージをホストしている場合は、この属性を使用してクエリ文字列に基づくイメージ バリアントを取得することによって、またはクエリ文字列を無視し、クエリ文字列せずに指定されたイメージを返すことで、クエリ文字列を処理できるとします。 このクエリ文字列は、スケール、コントラスト設定、および言語を指定します。値のインスタンス、 <c>www.website.com/images/hello.png</c>通知に含まれるなります<c>www.website.com/images/hello.png?ms-scale=100&amp;ms コントラスト = 標準&amp;ms lang = en-us</c>です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public string BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As String" />
      <MemberSignature Language="F#" Value="member this.BaseUri : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1056:UriPropertiesShouldNotBeStrings", Justification="XmlSerializer doesn't handle System.Uri")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("baseUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            既定のベース URI を相対 Uri で画像のソース属性と組み合わせて使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Branding">
      <MemberSignature Language="C#" Value="public string Branding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Branding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.Branding" />
      <MemberSignature Language="VB.NET" Value="Public Property Branding As String" />
      <MemberSignature Language="F#" Value="member this.Branding : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.Branding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("branding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タイルを使用して、アプリのブランドを表示するフォームです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentId">
      <MemberSignature Language="C#" Value="public string ContentId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.ContentId" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentId As String" />
      <MemberSignature Language="F#" Value="member this.ContentId : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.ContentId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("contentId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            通知のコンテンツを一意に識別する送信者定義の文字列に設定されます。 これは、大規模なタイル テンプレートが最後の 3 つのワイド タイル通知を表示するような状況での重複を防ぎます。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fallback">
      <MemberSignature Language="C#" Value="public string Fallback { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.Fallback" />
      <MemberSignature Language="VB.NET" Value="Public Property Fallback As String" />
      <MemberSignature Language="F#" Value="member this.Fallback : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.Fallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("fallback")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プライマリ テンプレート名が使用する Windows 8 の互換性のため、受信側で認識されない場合に使用するテンプレートです。 この値は、Windows 8 の名テンプレートの属性の値です。 Windows 8 以降後に導入された新しいテンプレートには、フォールバックがありません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Images">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileImage&gt; Images { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Mobile.Server.TileImage&gt; Images" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.Images" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Images As Collection(Of TileImage)" />
      <MemberSignature Language="F#" Value="member this.Images : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileImage&gt;" Usage="Microsoft.Azure.Mobile.Server.TileBinding.Images" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlElement("image")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileImage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            設定<see cref="T:Microsoft.Azure.Mobile.Server.TileImage" />要素
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lang">
      <MemberSignature Language="C#" Value="public string Lang { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Lang" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.Lang" />
      <MemberSignature Language="VB.NET" Value="Public Property Lang As String" />
      <MemberSignature Language="F#" Value="member this.Lang : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.Lang" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("lang")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Bcp-47 の言語などのタグとして指定された XML ペイロードの対象となるロケール<c>EN-US</c>または<c>FR-FR</c>です。 ここで指定されたロケールでは、任意の他の指定されたロケール、バインディングまたはビジュアルになどをオーバーライドします。 この値がリテラル文字列の場合は、この属性の既定値であるユーザーの UI 言語が使用します。 この値が文字列の参照の場合は、この属性の既定値は、文字列の解決に、Windows ランタイムによって選択されたロケールにします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Template">
      <MemberSignature Language="C#" Value="public string Template { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Template" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.Template" />
      <MemberSignature Language="VB.NET" Value="Public Property Template As String" />
      <MemberSignature Language="F#" Value="member this.Template : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.Template" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("template")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タイルの基になるで提供されているテンプレートの 1 つ。 通常、開発者では、四角形とワイド形式、それぞれを個別のバインド要素としての両方を指定する必要があります。 有効なエントリは、tileTemplateType 列挙体のメンバーです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Texts">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileText&gt; Texts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Mobile.Server.TileText&gt; Texts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.Texts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Texts As Collection(Of TileText)" />
      <MemberSignature Language="F#" Value="member this.Texts : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileText&gt;" Usage="Microsoft.Azure.Mobile.Server.TileBinding.Texts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlElement("text")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileText&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            設定<see cref="T:Microsoft.Azure.Mobile.Server.TileText" />要素
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>