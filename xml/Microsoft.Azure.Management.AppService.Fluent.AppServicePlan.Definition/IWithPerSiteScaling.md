<Type Name="IWithPerSiteScaling" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithPerSiteScaling">
  <TypeSignature Language="C#" Value="public interface IWithPerSiteScaling" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPerSiteScaling" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithPerSiteScaling" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPerSiteScaling" />
  <TypeSignature Language="F#" Value="type IWithPerSiteScaling = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2aa10-101">App service では、定義を許可する 1 つのサイトの構成をスケール設定を計画します。</span><span class="sxs-lookup"><span data-stu-id="2aa10-101">An app service plan definition allowing per site scaling configuration to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPerSiteScaling">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate WithPerSiteScaling (bool perSiteScaling);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate WithPerSiteScaling(bool perSiteScaling) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithPerSiteScaling.WithPerSiteScaling(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPerSiteScaling (perSiteScaling As Boolean) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPerSiteScaling : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate" Usage="iWithPerSiteScaling.WithPerSiteScaling perSiteScaling" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="perSiteScaling" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="perSiteScaling"><span data-ttu-id="2aa10-102">各サイトは、個別に拡張できます。 場合、</span><span class="sxs-lookup"><span data-stu-id="2aa10-102">If each site can be scaled individually.</span></span></param>
        <summary>
            <span data-ttu-id="2aa10-103">かどうかのサイトのスケーリングはオンにするかを指定します。</span><span class="sxs-lookup"><span data-stu-id="2aa10-103">Specifies whether per-site scaling will be turned on.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2aa10-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="2aa10-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>