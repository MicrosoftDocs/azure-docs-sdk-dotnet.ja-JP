<Type Name="MpnsTileMessage" FullName="Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage">
  <TypeSignature Language="C#" Value="public abstract class MpnsTileMessage : Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MpnsTileMessage extends Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MpnsTileMessage&#xA;Inherits MpnsMessage" />
  <TypeSignature Language="F#" Value="type MpnsTileMessage = class&#xA;    inherit MpnsMessage" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="96497-101">によって使用されるすべての MPNS タイルの抽象基本クラス<see cref="T:Microsoft.Azure.Mobile.Server.MpnsPushMessage" />および関連クラスです。</span><span class="sxs-lookup"><span data-stu-id="96497-101">Abstract base class for all MPNS tiles used by <see cref="T:Microsoft.Azure.Mobile.Server.MpnsPushMessage" /> and related classes.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="96497-102">このクラスは、直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="96497-102">This class is not intended for direct use.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MpnsTileMessage (string version, string template);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string version, string template) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (version As String, template As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage : string * string -&gt; Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" Usage="new Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage (version, template)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="template" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="version"><span data-ttu-id="96497-103">タイルのバージョン。</span><span class="sxs-lookup"><span data-stu-id="96497-103">The version of the tile.</span></span></param>
        <param name="template"><span data-ttu-id="96497-104">テンプレートの名前。</span><span class="sxs-lookup"><span data-stu-id="96497-104">The name of the template.</span></span></param>
        <summary>
            <span data-ttu-id="96497-105">新しい初期化<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" />で実装が、指定された<paramref name="version" />と<paramref name="template" />です。</span><span class="sxs-lookup"><span data-stu-id="96497-105">Initializes a new <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" /> implementation with a given <paramref name="version" /> and <paramref name="template" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96497-106">取得または 1 ~ 99 のタイルのカウント フィールドに表示される値を設定します。</span><span class="sxs-lookup"><span data-stu-id="96497-106">Gets or sets a value between 1 and 99 that will be displayed in the Count field of the Tile.</span></span> <span data-ttu-id="96497-107">値の 0 の場合は、カウントは表示されません。</span><span class="sxs-lookup"><span data-stu-id="96497-107">A value of 0 means the Count will not be displayed.</span></span> <span data-ttu-id="96497-108">このプロパティが設定されていない場合、カウントの表示は更新中に変更されません。</span><span class="sxs-lookup"><span data-stu-id="96497-108">If this property is not set, the Count display will not change during an update.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96497-109">取得または省略可能な ID またはタイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="96497-109">Gets or sets the optional ID or the tile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Title">
      <MemberSignature Language="C#" Value="public string Title { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Title" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.Title" />
      <MemberSignature Language="VB.NET" Value="Public Property Title As String" />
      <MemberSignature Language="F#" Value="member this.Title : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.Title" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96497-110">取得または中規模およびワイド タイルのサイズの前面に表示されるテキストを設定します。</span><span class="sxs-lookup"><span data-stu-id="96497-110">Gets or sets the text that displays on the front side of the medium and wide tile sizes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>