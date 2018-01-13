<Type Name="IWithParameters" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithParameters">
  <TypeSignature Language="C#" Value="public interface IWithParameters" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithParameters" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithParameters" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithParameters" />
  <TypeSignature Language="F#" Value="type IWithParameters = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            パラメーターを変更できるようにする展開の更新。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithParameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithParameters (object parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithParameters(object parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithParameters.WithParameters(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParameters (parameters As Object) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithParameters : obj -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate" Usage="iWithParameters.WithParameters parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="parameters">オブジェクト</param>
        <summary>
            オブジェクトとしてパラメーターを指定します。
            </summary>
        <returns>更新プログラムの展開の次のステージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithParameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithParameters (string parametersJson);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithParameters(string parametersJson) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithParameters.WithParameters(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParameters (parametersJson As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithParameters : string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate" Usage="iWithParameters.WithParameters parametersJson" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parametersJson" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parametersJson">parametersJson JSON 文字列</param>
        <summary>
            JSON 文字列として、パラメーターを指定します。
            </summary>
        <returns>更新プログラムの展開の次のステージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithParametersLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithParametersLink (string uri, string contentVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithParametersLink(string uri, string contentVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithParameters.WithParametersLink(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParametersLink (uri As String, contentVersion As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithParametersLink : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate" Usage="iWithParameters.WithParametersLink (uri, contentVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.String" />
        <Parameter Name="contentVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="uri">uri パラメーターをリモート ファイルの場所</param>
        <param name="contentVersion">contentVersion パラメーター ファイルのバージョン</param>
        <summary>
            URL としてパラメーターを指定します。
            </summary>
        <returns>更新プログラムの展開の次のステージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>