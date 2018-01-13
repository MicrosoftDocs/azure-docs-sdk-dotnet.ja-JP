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
            関数アプリを更新できるようにするランタイム バージョンを指定します。
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
            関数アプリの最新のランタイム バージョンを使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>関数アプリの更新プログラムの次のステージ。</return>
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
        <param name="version">Azure 関数のランタイムのバージョン。</param>
        <summary>
            関数アプリのランタイムのバージョンを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>関数アプリの更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>