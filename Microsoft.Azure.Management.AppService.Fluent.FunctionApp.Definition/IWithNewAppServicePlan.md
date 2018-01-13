<Type Name="IWithNewAppServicePlan" FullName="Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithNewAppServicePlan">
  <TypeSignature Language="C#" Value="public interface IWithNewAppServicePlan" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNewAppServicePlan" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithNewAppServicePlan" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNewAppServicePlan" />
  <TypeSignature Language="F#" Value="type IWithNewAppServicePlan = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            App service プランに設定するを許可する関数アプリ定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithNewAppServicePlan (Microsoft.Azure.Management.AppService.Fluent.PricingTier pricingTier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithNewAppServicePlan(class Microsoft.Azure.Management.AppService.Fluent.PricingTier pricingTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithNewAppServicePlan.WithNewAppServicePlan(Microsoft.Azure.Management.AppService.Fluent.PricingTier)" />
      <MemberSignature Language="F#" Value="abstract member WithNewAppServicePlan : Microsoft.Azure.Management.AppService.Fluent.PricingTier -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate" Usage="iWithNewAppServicePlan.WithNewAppServicePlan pricingTier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithNewAppServicePlan (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt; appServicePlanCreatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithNewAppServicePlan(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt; appServicePlanCreatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithNewAppServicePlan.WithNewAppServicePlan(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewAppServicePlan (appServicePlanCreatable As ICreatable(Of IAppServicePlan)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewAppServicePlan : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate" Usage="iWithNewAppServicePlan.WithNewAppServicePlan appServicePlanCreatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewConsumptionPlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithNewConsumptionPlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithNewConsumptionPlan() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithNewAppServicePlan.WithNewConsumptionPlan" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewConsumptionPlan () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewConsumptionPlan : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate" Usage="iWithNewAppServicePlan.WithNewConsumptionPlan " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            使用する新しい消費プランを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewFreeAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithNewFreeAppServicePlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithNewFreeAppServicePlan() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithNewAppServicePlan.WithNewFreeAppServicePlan" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewFreeAppServicePlan () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewFreeAppServicePlan : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate" Usage="iWithNewAppServicePlan.WithNewFreeAppServicePlan " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            新しい free app service プランを作成します。 これにより、現在のサブスクリプションに 10 または複数の無料の計画がある場合は失敗します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewSharedAppServicePlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithNewSharedAppServicePlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithNewSharedAppServicePlan() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithNewAppServicePlan.WithNewSharedAppServicePlan" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSharedAppServicePlan () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSharedAppServicePlan : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate" Usage="iWithNewAppServicePlan.WithNewSharedAppServicePlan " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            新しい共有の app service プランを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>