<Type Name="VisualTile" FullName="Microsoft.Azure.Mobile.Server.Notifications.VisualTile">
  <TypeSignature Language="C#" Value="public class VisualTile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VisualTile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Notifications.VisualTile" />
  <TypeSignature Language="VB.NET" Value="Public Class VisualTile" />
  <TypeSignature Language="F#" Value="type VisualTile = class" />
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
            このクラスを表します、 <c>visual</c> Windows Notification タイルの要素を参照してください<c>http://msdn.microsoft.com/en-us/library/windows/apps/hh761491.aspx</c>詳細についてはします。
            このクラスは、の一部として使用するものでは、<see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VisualTile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.VisualTile" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VisualTile (params Microsoft.Azure.Mobile.Server.TileBinding[] bindings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Mobile.Server.TileBinding[] bindings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.#ctor(Microsoft.Azure.Mobile.Server.TileBinding[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray bindings As TileBinding())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Notifications.VisualTile : Microsoft.Azure.Mobile.Server.TileBinding[] -&gt; Microsoft.Azure.Mobile.Server.Notifications.VisualTile" Usage="new Microsoft.Azure.Mobile.Server.Notifications.VisualTile bindings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bindings" Type="Microsoft.Azure.Mobile.Server.TileBinding[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="bindings">このバインディングの初期セット<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.VisualTile" />です。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.VisualTile" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddImageQuery">
      <MemberSignature Language="C#" Value="public bool AddImageQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AddImageQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.AddImageQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property AddImageQuery As Boolean" />
      <MemberSignature Language="F#" Value="member this.AddImageQuery : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.AddImageQuery" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As String" />
      <MemberSignature Language="F#" Value="member this.BaseUri : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.BaseUri" />
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
    <Member MemberName="Bindings">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileBinding&gt; Bindings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Mobile.Server.TileBinding&gt; Bindings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Bindings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Bindings As Collection(Of TileBinding)" />
      <MemberSignature Language="F#" Value="member this.Bindings : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileBinding&gt;" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Bindings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlElement("binding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileBinding&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" />タイル テンプレートを指定します。 通知ごとには、サポートされているタイル サイズごとに 1 つのバインド要素を含める必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Branding">
      <MemberSignature Language="C#" Value="public string Branding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Branding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Branding" />
      <MemberSignature Language="VB.NET" Value="Public Property Branding As String" />
      <MemberSignature Language="F#" Value="member this.Branding : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Branding" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.ContentId" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentId As String" />
      <MemberSignature Language="F#" Value="member this.ContentId : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.ContentId" />
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
    <Member MemberName="Lang">
      <MemberSignature Language="C#" Value="public string Lang { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Lang" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Lang" />
      <MemberSignature Language="VB.NET" Value="Public Property Lang As String" />
      <MemberSignature Language="F#" Value="member this.Lang : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Lang" />
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
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public int Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As Integer" />
      <MemberSignature Language="F#" Value="member this.Version : int with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(1)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タイルの XML スキーマのバージョンのこの特定のペイロードに開発されました。 2 つ持つことができます、値 1 または 2 です。 バージョン 1 には、Windows 8 のスキーマで有効なペイロードが必要です。 バージョン 2 は、新しい大きなタイル テンプレート、既存のテンプレートの新しい Windows 8.1 のテンプレート名とバインド要素のフォールバック属性を認識します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>