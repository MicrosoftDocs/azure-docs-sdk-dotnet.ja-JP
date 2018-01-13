<Type Name="FabricClient+ClaimsRetrievalEventArgs" FullName="System.Fabric.FabricClient+ClaimsRetrievalEventArgs">
  <TypeSignature Language="C#" Value="public class FabricClient.ClaimsRetrievalEventArgs : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi beforefieldinit FabricClient/ClaimsRetrievalEventArgs extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ClaimsRetrievalEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricClient.ClaimsRetrievalEventArgs&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type FabricClient.ClaimsRetrievalEventArgs = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            要求トークンの取得イベントのイベント引数を表します
            </summary>
    <remarks>アプリケーション承認要求トークンを提供することもできます。</remarks>
  </Docs>
  <Members>
    <Member MemberName="AzureActiveDirectoryMetadata">
      <MemberSignature Language="C#" Value="public System.Fabric.Security.AzureActiveDirectoryMetadata AzureActiveDirectoryMetadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Security.AzureActiveDirectoryMetadata AzureActiveDirectoryMetadata" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ClaimsRetrievalEventArgs.AzureActiveDirectoryMetadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AzureActiveDirectoryMetadata As AzureActiveDirectoryMetadata" />
      <MemberSignature Language="F#" Value="member this.AzureActiveDirectoryMetadata : System.Fabric.Security.AzureActiveDirectoryMetadata" Usage="System.Fabric.FabricClient.ClaimsRetrievalEventArgs.AzureActiveDirectoryMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Security.AzureActiveDirectoryMetadata</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Active Directory からの要求トークンを取得するために必要なメタデータを取得します。
            </summary>
        <value>メタデータ オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>