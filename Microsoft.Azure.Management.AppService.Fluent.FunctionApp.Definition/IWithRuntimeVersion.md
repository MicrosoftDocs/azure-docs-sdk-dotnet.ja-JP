<Type Name="IWithRuntimeVersion" FullName="Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithRuntimeVersion">
  <TypeSignature Language="C#" Value="public interface IWithRuntimeVersion" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRuntimeVersion" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithRuntimeVersion" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRuntimeVersion" />
  <TypeSignature Language="F#" Value="type IWithRuntimeVersion = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ランタイム バージョンを指定するを許可する関数アプリ定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLatestRuntimeVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithLatestRuntimeVersion ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithLatestRuntimeVersion() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithRuntimeVersion.WithLatestRuntimeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLatestRuntimeVersion () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithLatestRuntimeVersion : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate" Usage="iWithRuntimeVersion.WithLatestRuntimeVersion " />
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
            関数アプリの最新のランタイム バージョンを使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithRuntimeVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithRuntimeVersion (string version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithRuntimeVersion(string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithRuntimeVersion.WithRuntimeVersion(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRuntimeVersion (version As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRuntimeVersion : string -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate" Usage="iWithRuntimeVersion.WithRuntimeVersion version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>