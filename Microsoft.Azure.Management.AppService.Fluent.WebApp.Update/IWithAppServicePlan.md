<Type Name="IWithAppServicePlan" FullName="Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithAppServicePlan">
  <TypeSignature Language="C#" Value="public interface IWithAppServicePlan" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAppServicePlan" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithAppServicePlan" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAppServicePlan" />
  <TypeSignature Language="F#" Value="type IWithAppServicePlan = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Web アプリを設定する許可アプリ サービス プランを更新します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithExistingAppServicePlan (Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan appServicePlan);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithExistingAppServicePlan(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan appServicePlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithAppServicePlan.WithExistingAppServicePlan(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingAppServicePlan (appServicePlan As IAppServicePlan) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingAppServicePlan : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate" Usage="iWithAppServicePlan.WithExistingAppServicePlan appServicePlan" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan" />
      </Parameters>
      <Docs>
        <param name="appServicePlan">既存の app service プランです。</param>
        <summary>
            Web アプリの既存の app service プランを使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithNewAppServicePlan (Microsoft.Azure.Management.AppService.Fluent.PricingTier pricingTier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithNewAppServicePlan(class Microsoft.Azure.Management.AppService.Fluent.PricingTier pricingTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithAppServicePlan.WithNewAppServicePlan(Microsoft.Azure.Management.AppService.Fluent.PricingTier)" />
      <MemberSignature Language="F#" Value="abstract member WithNewAppServicePlan : Microsoft.Azure.Management.AppService.Fluent.PricingTier -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate" Usage="iWithAppServicePlan.WithNewAppServicePlan pricingTier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pricingTier" Type="Microsoft.Azure.Management.AppService.Fluent.PricingTier" />
      </Parameters>
      <Docs>
        <param name="pricingTier">App service プランの sku。</param>
        <summary>
            使用する新しい app service プランを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithNewAppServicePlan (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt; appServicePlanCreatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithNewAppServicePlan(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt; appServicePlanCreatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithAppServicePlan.WithNewAppServicePlan(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewAppServicePlan (appServicePlanCreatable As ICreatable(Of IAppServicePlan)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewAppServicePlan : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate" Usage="iWithAppServicePlan.WithNewAppServicePlan appServicePlanCreatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appServicePlanCreatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt;" />
      </Parameters>
      <Docs>
        <param name="appServicePlanCreatable">新しい app service プラン作成可能です。</param>
        <summary>
            使用する新しい app service プランを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewFreeAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithNewFreeAppServicePlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithNewFreeAppServicePlan() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithAppServicePlan.WithNewFreeAppServicePlan" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewFreeAppServicePlan () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewFreeAppServicePlan : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate" Usage="iWithAppServicePlan.WithNewFreeAppServicePlan " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            新しい free app service プランを作成します。 これにより、現在のサブスクリプションに 10 または複数の無料の計画がある場合は失敗します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewSharedAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithNewSharedAppServicePlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithNewSharedAppServicePlan() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithAppServicePlan.WithNewSharedAppServicePlan" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSharedAppServicePlan () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSharedAppServicePlan : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate" Usage="iWithAppServicePlan.WithNewSharedAppServicePlan " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            新しい共有の app service プランを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>