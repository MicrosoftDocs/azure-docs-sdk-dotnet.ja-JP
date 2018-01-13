<Type Name="IWithFqdn" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithFqdn">
  <TypeSignature Language="C#" Value="public interface IWithFqdn" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFqdn" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithFqdn" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFqdn" />
  <TypeSignature Language="F#" Value="type IWithFqdn = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            外部エンドポイントの更新を許可する FQDN を指定するの段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateExternalEndpoint.IUpdateExternalEndpoint ToFqdn (string externalFqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateExternalEndpoint.IUpdateExternalEndpoint ToFqdn(string externalFqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithFqdn.ToFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToFqdn (externalFqdn As String) As IUpdateExternalEndpoint" />
      <MemberSignature Language="F#" Value="abstract member ToFqdn : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateExternalEndpoint.IUpdateExternalEndpoint" Usage="iWithFqdn.ToFqdn externalFqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateExternalEndpoint.IUpdateExternalEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="externalFqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="externalFqdn">外部 FQDN。</param>
        <summary>
            Azure でホストされていない外部エンドポイントの FQDN を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>エンドポイントの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>