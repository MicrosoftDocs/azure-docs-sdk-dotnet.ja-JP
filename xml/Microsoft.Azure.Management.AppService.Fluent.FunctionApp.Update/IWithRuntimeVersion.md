<Type Name="IWithRuntimeVersion" FullName="Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithRuntimeVersion">
  <TypeSignature Language="C#" Value="public interface IWithRuntimeVersion" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRuntimeVersion" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithRuntimeVersion" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRuntimeVersion" />
  <TypeSignature Language="F#" Value="type IWithRuntimeVersion = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e38d6-101">関数アプリを更新できるようにするランタイム バージョンを指定します。</span><span class="sxs-lookup"><span data-stu-id="e38d6-101">A function app update allowing runtime version to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLatestRuntimeVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithLatestRuntimeVersion ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithLatestRuntimeVersion() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithRuntimeVersion.WithLatestRuntimeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLatestRuntimeVersion () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithLatestRuntimeVersion : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate" Usage="iWithRuntimeVersion.WithLatestRuntimeVersion " />
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
            <span data-ttu-id="e38d6-102">関数アプリの最新のランタイム バージョンを使用します。</span><span class="sxs-lookup"><span data-stu-id="e38d6-102">Uses the latest runtime version for the function app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e38d6-103">関数アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e38d6-103">The next stage of the function app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRuntimeVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithRuntimeVersion (string version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithRuntimeVersion(string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithRuntimeVersion.WithRuntimeVersion(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRuntimeVersion (version As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRuntimeVersion : string -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate" Usage="iWithRuntimeVersion.WithRuntimeVersion version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="version"><span data-ttu-id="e38d6-104">Azure 関数のランタイムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="e38d6-104">The version of the Azure Functions runtime.</span></span></param>
        <summary>
            <span data-ttu-id="e38d6-105">関数アプリのランタイムのバージョンを指定します。</span><span class="sxs-lookup"><span data-stu-id="e38d6-105">Specifies the runtime version for the function app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e38d6-106">関数アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e38d6-106">The next stage of the function app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>