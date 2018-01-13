<Type Name="IWithApplication" FullName="Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication">
  <TypeSignature Language="C#" Value="public interface IWithApplication" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithApplication" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithApplication" />
  <TypeSignature Language="F#" Value="type IWithApplication = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f7a78-101">バッチのアプリケーションの作成を許可するバッチ アカウント定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="f7a78-101">The stage of a Batch account definition allowing the creation of a Batch application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewApplication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt; DefineNewApplication (string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt; DefineNewApplication(string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication.DefineNewApplication(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewApplication (applicationId As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewApplication : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt;" Usage="iWithApplication.DefineNewApplication applicationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationId"><span data-ttu-id="f7a78-102">アプリケーションの参照名。</span><span class="sxs-lookup"><span data-stu-id="f7a78-102">The reference name for the application.</span></span></param>
        <summary>
            <span data-ttu-id="f7a78-103">Batch アカウントに作成されるアプリケーションの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7a78-103">Starts a definition of an application to be created in the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f7a78-104">バッチのアプリケーション定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="f7a78-104">The first stage of a Batch application definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate UpdateApplication (string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate UpdateApplication(string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication.UpdateApplication(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateApplication (applicationId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateApplication : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate" Usage="iWithApplication.UpdateApplication applicationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationId"><span data-ttu-id="f7a78-105">更新するアプリケーションの参照名。</span><span class="sxs-lookup"><span data-stu-id="f7a78-105">The reference name of the application to be updated.</span></span></param>
        <summary>
            <span data-ttu-id="f7a78-106">この Batch アカウントの既存のバッチ アプリケーションの更新プログラムの説明を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7a78-106">Begins the description of an update of an existing Batch application in this Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f7a78-107">バッチのアプリケーションの更新プログラムの最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="f7a78-107">The first stage of a Batch application update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutApplication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithoutApplication (string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithoutApplication(string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication.WithoutApplication(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutApplication (applicationId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutApplication : string -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate" Usage="iWithApplication.WithoutApplication applicationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationId"><span data-ttu-id="f7a78-108">削除するアプリケーションの参照名です。</span><span class="sxs-lookup"><span data-stu-id="f7a78-108">The reference name for the application to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="f7a78-109">Batch アカウントから、指定したアプリケーションを削除します。</span><span class="sxs-lookup"><span data-stu-id="f7a78-109">Removes the specified application from the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f7a78-110">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f7a78-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>