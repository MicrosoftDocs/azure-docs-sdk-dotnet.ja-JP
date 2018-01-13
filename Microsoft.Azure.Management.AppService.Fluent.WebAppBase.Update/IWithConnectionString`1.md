<Type Name="IWithConnectionString&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithConnectionString&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithConnectionString`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithConnectionString(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithConnectionString&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT"><span data-ttu-id="8fd3b-101">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="8fd3b-102">Web アプリは、段階の許可を設定する接続文字列を更新します。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-102">A web app update stage allowing connection strings to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithConnectionString (string name, string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithConnectionString(string name, string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1.WithConnectionString(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConnectionString (name As String, value As String, type As ConnectionStringType) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithConnectionString : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithConnectionString (name, value, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8fd3b-103">接続文字列の名前。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-103">The name of the connection string.</span></span></param>
        <param name="value"><span data-ttu-id="8fd3b-104">接続文字列の値。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-104">The connection string value.</span></span></param>
        <param name="type"><span data-ttu-id="8fd3b-105">接続文字列の種類。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-105">The connection string type.</span></span></param>
        <summary>
            <span data-ttu-id="8fd3b-106">Web アプリを接続文字列を追加します。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-106">Adds a connection string to the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8fd3b-107">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-107">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithConnectionStringStickiness">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithConnectionStringStickiness (string name, bool sticky);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithConnectionStringStickiness(string name, bool sticky) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1.WithConnectionStringStickiness(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConnectionStringStickiness (name As String, sticky As Boolean) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithConnectionStringStickiness : string * bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithConnectionStringStickiness (name, sticky)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sticky" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8fd3b-108">接続文字列の名前。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-108">The name of the connection string.</span></span></param>
        <param name="sticky"><span data-ttu-id="8fd3b-109">スワップの間に、スロットに接続文字列が見やすいようにアレンジする場合は true。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-109">True if the connection string sticks to the slot during a swap.</span></span></param>
        <summary>
            <span data-ttu-id="8fd3b-110">接続文字列の貼り付けを変更します。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-110">Changes the stickiness of a connection string.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8fd3b-111">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-111">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutConnectionString (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutConnectionString(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1.WithoutConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutConnectionString (name As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutConnectionString : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithoutConnectionString name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8fd3b-112">接続文字列の名前。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-112">The name of the connection string.</span></span></param>
        <summary>
            <span data-ttu-id="8fd3b-113">Web アプリからの接続文字列を削除します。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-113">Removes a connection string from the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8fd3b-114">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-114">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithStickyConnectionString (string name, string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithStickyConnectionString(string name, string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1.WithStickyConnectionString(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyConnectionString (name As String, value As String, type As ConnectionStringType) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyConnectionString : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithStickyConnectionString (name, value, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8fd3b-115">接続文字列の名前。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-115">The name of the connection string.</span></span></param>
        <param name="value"><span data-ttu-id="8fd3b-116">接続文字列の値。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-116">The connection string value.</span></span></param>
        <param name="type"><span data-ttu-id="8fd3b-117">接続文字列の種類。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-117">The connection string type.</span></span></param>
        <summary>
            <span data-ttu-id="8fd3b-118">Web アプリを接続文字列を追加します。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-118">Adds a connection string to the web app.</span></span> <span data-ttu-id="8fd3b-119">この接続文字列は、スロットのスワップの間に維持されます。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-119">This connection string will stay at the slot during a swap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8fd3b-120">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="8fd3b-120">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>