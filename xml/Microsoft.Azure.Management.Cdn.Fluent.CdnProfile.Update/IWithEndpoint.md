<Type Name="IWithEndpoint" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint">
  <TypeSignature Language="C#" Value="public interface IWithEndpoint : Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpointBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithEndpoint implements class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpointBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithEndpoint&#xA;Implements IBeta, IWithEndpointBeta" />
  <TypeSignature Language="F#" Value="type IWithEndpoint = interface&#xA;    interface IWithEndpointBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpointBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="eb556-101">プロファイルのエンドポイントの変更を許可する CDN プロファイルの更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="eb556-101">The stage of a CDN profile update allowing to modify the endpoints for the profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.StandardEndpoint.IStandardEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt; DefineNewEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.StandardEndpoint.IStandardEndpoint`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt; DefineNewEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.DefineNewEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewEndpoint (name As String) As IStandardEndpoint(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.StandardEndpoint.IStandardEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;" Usage="iWithEndpoint.DefineNewEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.StandardEndpoint.IStandardEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="eb556-102">エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="eb556-102">The name for the endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="eb556-103">CDN プロファイルに接続する新しいエンドポイントの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="eb556-103">Starts the definition of a new endpoint to be attached to the CDN profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eb556-104">エンドポイントの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="eb556-104">The first stage of an endpoint definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineNewPremiumEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.PremiumEndpoint.IPremiumEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt; DefineNewPremiumEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.PremiumEndpoint.IPremiumEndpoint`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt; DefineNewPremiumEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.DefineNewPremiumEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewPremiumEndpoint (name As String) As IPremiumEndpoint(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewPremiumEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.PremiumEndpoint.IPremiumEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;" Usage="iWithEndpoint.DefineNewPremiumEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.PremiumEndpoint.IPremiumEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="eb556-105">新しいエンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="eb556-105">A name for the new endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="eb556-106">この Premium Verizon CDN プロファイルに接続する新しいエンドポイントの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="eb556-106">Starts the definition of a new endpoint to be attached to this Premium Verizon CDN profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eb556-107">エンドポイントの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="eb556-107">The first stage of an endpoint definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint UpdateEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint UpdateEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.UpdateEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateEndpoint (name As String) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member UpdateEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iWithEndpoint.UpdateEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="eb556-108">既存のエンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="eb556-108">The name of an existing endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="eb556-109">現在のプロファイルで既存のエンドポイントの更新プログラムの説明を開始します。</span><span class="sxs-lookup"><span data-stu-id="eb556-109">Begins the description of an update of an existing endpoint in current profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eb556-110">エンドポイントの更新プログラムの最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="eb556-110">The first stage of the update of the endpoint.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdatePremiumEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdatePremiumEndpoint.IUpdatePremiumEndpoint UpdatePremiumEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdatePremiumEndpoint.IUpdatePremiumEndpoint UpdatePremiumEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.UpdatePremiumEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdatePremiumEndpoint (name As String) As IUpdatePremiumEndpoint" />
      <MemberSignature Language="F#" Value="abstract member UpdatePremiumEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdatePremiumEndpoint.IUpdatePremiumEndpoint" Usage="iWithEndpoint.UpdatePremiumEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdatePremiumEndpoint.IUpdatePremiumEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="eb556-111">エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="eb556-111">The name of the endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="eb556-112">現在の Premium Verizon プロファイルで既存のエンドポイントの更新プログラムの説明を開始します。</span><span class="sxs-lookup"><span data-stu-id="eb556-112">Begins the description of an update of an existing endpoint in current Premium Verizon profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eb556-113">エンドポイントの更新プログラムの最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="eb556-113">The first stage of the update of the endpoint.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate WithNewEndpoint (string endpointOriginHostname);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate WithNewEndpoint(string endpointOriginHostname) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.WithNewEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewEndpoint (endpointOriginHostname As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate" Usage="iWithEndpoint.WithNewEndpoint endpointOriginHostname" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointOriginHostname" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointOriginHostname"><span data-ttu-id="eb556-114">エンドポイント配信元ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="eb556-114">An endpoint origin hostname.</span></span></param>
        <summary>
            <span data-ttu-id="eb556-115">新しいエンドポイントを追加します。</span><span class="sxs-lookup"><span data-stu-id="eb556-115">Adds a new endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eb556-116">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="eb556-116">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPremiumEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate WithNewPremiumEndpoint (string endpointOriginHostname);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate WithNewPremiumEndpoint(string endpointOriginHostname) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.WithNewPremiumEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPremiumEndpoint (endpointOriginHostname As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPremiumEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate" Usage="iWithEndpoint.WithNewPremiumEndpoint endpointOriginHostname" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointOriginHostname" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointOriginHostname"><span data-ttu-id="eb556-117">エンドポイントの配信元ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="eb556-117">The endpoint origin hostname.</span></span></param>
        <summary>
            <span data-ttu-id="eb556-118">現在の Premium Verizon CDN プロファイルに新しいエンドポイントを追加します。</span><span class="sxs-lookup"><span data-stu-id="eb556-118">Adds new endpoint to current Premium Verizon CDN profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eb556-119">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="eb556-119">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate WithoutEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate WithoutEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.WithoutEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutEndpoint (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate" Usage="iWithEndpoint.WithoutEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="eb556-120">既存のエンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="eb556-120">The name of an existing endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="eb556-121">プロファイルからエンドポイントを削除します。</span><span class="sxs-lookup"><span data-stu-id="eb556-121">Removes an endpoint from the profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eb556-122">CDN プロファイルの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="eb556-122">The next stage of the CDN profile update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>