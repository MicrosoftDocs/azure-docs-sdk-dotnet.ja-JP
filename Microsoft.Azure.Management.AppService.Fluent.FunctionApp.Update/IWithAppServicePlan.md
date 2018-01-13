<Type Name="IWithAppServicePlan" FullName="Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithAppServicePlan">
  <TypeSignature Language="C#" Value="public interface IWithAppServicePlan" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAppServicePlan" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithAppServicePlan" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAppServicePlan" />
  <TypeSignature Language="F#" Value="type IWithAppServicePlan = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fff97-101">関数アプリでは、設定にすることができますの app service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="fff97-101">A function app update allowing app service plan to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithExistingAppServicePlan (Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan appServicePlan);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithExistingAppServicePlan(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan appServicePlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithAppServicePlan.WithExistingAppServicePlan(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingAppServicePlan (appServicePlan As IAppServicePlan) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingAppServicePlan : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate" Usage="iWithAppServicePlan.WithExistingAppServicePlan appServicePlan" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan" />
      </Parameters>
      <Docs>
        <param name="appServicePlan"><span data-ttu-id="fff97-102">既存の app service プランです。</span><span class="sxs-lookup"><span data-stu-id="fff97-102">The existing app service plan.</span></span></param>
        <summary>
            <span data-ttu-id="fff97-103">関数アプリの既存の app service プランを使用します。</span><span class="sxs-lookup"><span data-stu-id="fff97-103">Uses an existing app service plan for the function app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fff97-104">関数アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="fff97-104">The next stage of the function app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithNewAppServicePlan (Microsoft.Azure.Management.AppService.Fluent.PricingTier pricingTier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithNewAppServicePlan(class Microsoft.Azure.Management.AppService.Fluent.PricingTier pricingTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithAppServicePlan.WithNewAppServicePlan(Microsoft.Azure.Management.AppService.Fluent.PricingTier)" />
      <MemberSignature Language="F#" Value="abstract member WithNewAppServicePlan : Microsoft.Azure.Management.AppService.Fluent.PricingTier -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate" Usage="iWithAppServicePlan.WithNewAppServicePlan pricingTier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pricingTier" Type="Microsoft.Azure.Management.AppService.Fluent.PricingTier" />
      </Parameters>
      <Docs>
        <param name="pricingTier"><span data-ttu-id="fff97-105">App service プランの sku。</span><span class="sxs-lookup"><span data-stu-id="fff97-105">The sku of the app service plan.</span></span></param>
        <summary>
            <span data-ttu-id="fff97-106">使用する新しい app service プランを作成します。</span><span class="sxs-lookup"><span data-stu-id="fff97-106">Creates a new app service plan to use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fff97-107">関数アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="fff97-107">The next stage of the function app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithNewAppServicePlan (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt; appServicePlanCreatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithNewAppServicePlan(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt; appServicePlanCreatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithAppServicePlan.WithNewAppServicePlan(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewAppServicePlan (appServicePlanCreatable As ICreatable(Of IAppServicePlan)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewAppServicePlan : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate" Usage="iWithAppServicePlan.WithNewAppServicePlan appServicePlanCreatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appServicePlanCreatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt;" />
      </Parameters>
      <Docs>
        <param name="appServicePlanCreatable"><span data-ttu-id="fff97-108">新しい app service プラン作成可能です。</span><span class="sxs-lookup"><span data-stu-id="fff97-108">The new app service plan creatable.</span></span></param>
        <summary>
            <span data-ttu-id="fff97-109">使用する新しい app service プランを作成します。</span><span class="sxs-lookup"><span data-stu-id="fff97-109">Creates a new app service plan to use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fff97-110">関数アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="fff97-110">The next stage of the function app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewConsumptionPlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithNewConsumptionPlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithNewConsumptionPlan() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithAppServicePlan.WithNewConsumptionPlan" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewConsumptionPlan () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewConsumptionPlan : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate" Usage="iWithAppServicePlan.WithNewConsumptionPlan " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fff97-111">使用する新しい消費プランを作成します。</span><span class="sxs-lookup"><span data-stu-id="fff97-111">Creates a new consumption plan to use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fff97-112">関数アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="fff97-112">The next stage of the function app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewFreeAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithNewFreeAppServicePlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithNewFreeAppServicePlan() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithAppServicePlan.WithNewFreeAppServicePlan" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewFreeAppServicePlan () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewFreeAppServicePlan : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate" Usage="iWithAppServicePlan.WithNewFreeAppServicePlan " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fff97-113">新しい free app service プランを作成します。</span><span class="sxs-lookup"><span data-stu-id="fff97-113">Creates a new free app service plan.</span></span> <span data-ttu-id="fff97-114">これにより、現在のサブスクリプションに 10 または複数の無料の計画がある場合は失敗します。</span><span class="sxs-lookup"><span data-stu-id="fff97-114">This will fail if there are 10 or more free plans in the current subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fff97-115">関数アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="fff97-115">The next stage of the function app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewSharedAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithNewSharedAppServicePlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithNewSharedAppServicePlan() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithAppServicePlan.WithNewSharedAppServicePlan" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSharedAppServicePlan () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSharedAppServicePlan : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate" Usage="iWithAppServicePlan.WithNewSharedAppServicePlan " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fff97-116">新しい共有の app service プランを作成します。</span><span class="sxs-lookup"><span data-stu-id="fff97-116">Creates a new shared app service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fff97-117">関数アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="fff97-117">The next stage of the function app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>