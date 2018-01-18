<Type Name="TileImage" FullName="Microsoft.Azure.Mobile.Server.TileImage">
  <TypeSignature Language="C#" Value="public class TileImage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TileImage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.TileImage" />
  <TypeSignature Language="VB.NET" Value="Public Class TileImage" />
  <TypeSignature Language="F#" Value="type TileImage = class" />
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
            <span data-ttu-id="0b322-101">このクラスを表します、<c>イメージ</c>Windows Notification タイルの要素を参照してください<c>http://msdn.microsoft.com/en-us/library/windows/apps/hh761491.aspx</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="0b322-101">This class represents the <c>image</c> element of a Windows Notification tile, see <c>http://msdn.microsoft.com/en-us/library/windows/apps/hh761491.aspx</c> for details.</span></span>
            <span data-ttu-id="0b322-102">このクラスは、の一部として使用するものでは、<see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="0b322-102">This class is intended for use as part of the <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TileImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TileImage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddImageQuery">
      <MemberSignature Language="C#" Value="public bool AddImageQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AddImageQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileImage.AddImageQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property AddImageQuery As Boolean" />
      <MemberSignature Language="F#" Value="member this.AddImageQuery : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.TileImage.AddImageQuery" />
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
            <span data-ttu-id="0b322-103">イメージ タイル通知で指定された URI にクエリ文字列を追加するウィンドウを許可する場合は true に設定します。</span><span class="sxs-lookup"><span data-stu-id="0b322-103">Set to true to allow Windows to append a query string to the image URI supplied in the tile notification.</span></span> <span data-ttu-id="0b322-104">サーバー イメージをホストしている場合は、この属性を使用してクエリ文字列に基づくイメージ バリアントを取得することによって、またはクエリ文字列を無視し、クエリ文字列せずに指定されたイメージを返すことで、クエリ文字列を処理できるとします。</span><span class="sxs-lookup"><span data-stu-id="0b322-104">Use this attribute if your server hosts images and can handle query strings, either by retrieving an image variant based on the query strings or by ignoring the query string and returning the image as specified without the query string.</span></span> <span data-ttu-id="0b322-105">このクエリ文字列は、スケール、コントラスト設定、および言語を指定します。値のインスタンス、 <c>www.website.com/images/hello.png</c>通知に含まれるなります<c>www.website.com/images/hello.png?ms-scale=100&amp;ms コントラスト = 標準&amp;ms lang = en-us</c>です。</span><span class="sxs-lookup"><span data-stu-id="0b322-105">This query string specifies scale, contrast setting, and language; for instance, a value of <c>www.website.com/images/hello.png</c> included in the notification becomes <c>www.website.com/images/hello.png?ms-scale=100&amp;ms-contrast=standard&amp;ms-lang=en-us</c>.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Alt">
      <MemberSignature Language="C#" Value="public string Alt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Alt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileImage.Alt" />
      <MemberSignature Language="VB.NET" Value="Public Property Alt As String" />
      <MemberSignature Language="F#" Value="member this.Alt : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileImage.Alt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("alt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0b322-106">支援技術のユーザーに対して、イメージの説明です。</span><span class="sxs-lookup"><span data-stu-id="0b322-106">A description of the image, for users of assistive technologies.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public int Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileImage.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As Integer" />
      <MemberSignature Language="F#" Value="member this.Id : int with get, set" Usage="Microsoft.Azure.Mobile.Server.TileImage.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0b322-107">このイメージは、タイル テンプレート内のイメージ要素。</span><span class="sxs-lookup"><span data-stu-id="0b322-107">The image element in the tile template that this image is intended for.</span></span> <span data-ttu-id="0b322-108">テンプレートに 1 つだけのイメージがある場合は、この値は 1 です。</span><span class="sxs-lookup"><span data-stu-id="0b322-108">If a template has only one image, then this value is 1.</span></span> <span data-ttu-id="0b322-109">使用可能なイメージの位置の数は、テンプレートの定義に基づきます。</span><span class="sxs-lookup"><span data-stu-id="0b322-109">The number of available image positions is based on the template definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Src">
      <MemberSignature Language="C#" Value="public string Src { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Src" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileImage.Src" />
      <MemberSignature Language="VB.NET" Value="Public Property Src As String" />
      <MemberSignature Language="F#" Value="member this.Src : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileImage.Src" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("src")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0b322-110">画像の URI がソースこれらのプロトコル ハンドラーのいずれかの: <c>http://</c>または<c>https://</c> web ベースのイメージのことを意味<c>ms appx:///</c>アプリ パッケージに含まれているイメージの意味<c>ms appdata:///ローカル/</c>ローカル記憶域に保存されたイメージのことを意味し、 <c>file:///</c>ローカル イメージのことを意味します。</span><span class="sxs-lookup"><span data-stu-id="0b322-110">The URI of the image source, one of these protocol handlers: <c>http://</c> or <c>https://</c> means a web-based image, <c>ms-appx:///</c> means an image included in the app package, <c>ms-appdata:///local/</c> means an image saved to local storage, and <c>file:///</c> means a local image.</span></span> <span data-ttu-id="0b322-111">(デスクトップ アプリについてのみサポートされています。</span><span class="sxs-lookup"><span data-stu-id="0b322-111">(Supported only for desktop apps.</span></span> <span data-ttu-id="0b322-112">このプロトコルは使えません Windows ストア アプリによって。)</span><span class="sxs-lookup"><span data-stu-id="0b322-112">This protocol cannot be used by Windows Store apps.)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>