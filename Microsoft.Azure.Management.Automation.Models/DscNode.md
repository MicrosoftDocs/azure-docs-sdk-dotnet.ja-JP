<Type Name="DscNode" FullName="Microsoft.Azure.Management.Automation.Models.DscNode">
  <TypeSignature Language="C#" Value="public class DscNode : Microsoft.Azure.Management.Automation.Models.ResourceBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DscNode extends Microsoft.Azure.Management.Automation.Models.ResourceBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.DscNode" />
  <TypeSignature Language="VB.NET" Value="Public Class DscNode&#xA;Inherits ResourceBase" />
  <TypeSignature Language="F#" Value="type DscNode = class&#xA;    inherit ResourceBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Automation.Models.ResourceBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Dsc ノードの種類の定義。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DscNode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.DscNode.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DscNode クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public Guid AccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNode.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountId As Guid" />
      <MemberSignature Language="F#" Value="member this.AccountId : Guid with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNode.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 取得またはノードのアカウント id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ip">
      <MemberSignature Language="C#" Value="public string Ip { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Ip" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNode.Ip" />
      <MemberSignature Language="VB.NET" Value="Public Property Ip As String" />
      <MemberSignature Language="F#" Value="member this.Ip : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNode.Ip" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 取得またはノードの ip を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSeen">
      <MemberSignature Language="C#" Value="public DateTimeOffset LastSeen { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset LastSeen" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNode.LastSeen" />
      <MemberSignature Language="VB.NET" Value="Public Property LastSeen As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.LastSeen : DateTimeOffset with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNode.LastSeen" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 取得またはノードの最後に見られる時間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationAssociationProperty NodeConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationAssociationProperty NodeConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNode.NodeConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeConfiguration As DscNodeConfigurationAssociationProperty" />
      <MemberSignature Language="F#" Value="member this.NodeConfiguration : Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationAssociationProperty with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNode.NodeConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationAssociationProperty</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 取得またはノードの構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public Guid NodeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid NodeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNode.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeId As Guid" />
      <MemberSignature Language="F#" Value="member this.NodeId : Guid with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNode.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 取得またはノードの id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationTime">
      <MemberSignature Language="C#" Value="public DateTimeOffset RegistrationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset RegistrationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNode.RegistrationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RegistrationTime As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.RegistrationTime : DateTimeOffset with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNode.RegistrationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 取得またはノードの登録時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNode.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNode.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 取得またはノードの状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>