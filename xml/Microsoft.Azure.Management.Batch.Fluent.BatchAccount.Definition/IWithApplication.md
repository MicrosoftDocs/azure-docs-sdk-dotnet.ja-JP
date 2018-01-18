<Type Name="IWithApplication" FullName="Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithApplication">
  <TypeSignature Language="C#" Value="public interface IWithApplication" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithApplication" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithApplication" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithApplication" />
  <TypeSignature Language="F#" Value="type IWithApplication = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="89e58-101">バッチのアプリケーションの作成を許可するバッチ アカウント定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="89e58-101">The stage of a Batch account definition allowing the creation of a Batch application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewApplication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IBlank&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithApplicationAndStorage&gt; DefineNewApplication (string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithApplicationAndStorage&gt; DefineNewApplication(string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithApplication.DefineNewApplication(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewApplication (applicationId As String) As IBlank(Of IWithApplicationAndStorage)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewApplication : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IBlank&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithApplicationAndStorage&gt;" Usage="iWithApplication.DefineNewApplication applicationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Definition.IBlank&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithApplicationAndStorage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationId"><span data-ttu-id="89e58-102">作成するアプリケーションの id です。</span><span class="sxs-lookup"><span data-stu-id="89e58-102">The id of the application to create.</span></span></param>
        <summary>
            <span data-ttu-id="89e58-103">アプリケーションを追加するバッチを許可するバッチ アカウント定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="89e58-103">The stage of a Batch account definition allowing to add a Batch application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="89e58-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="89e58-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>