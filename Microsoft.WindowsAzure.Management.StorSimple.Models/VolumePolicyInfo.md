<Type Name="VolumePolicyInfo" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo">
  <TypeSignature Language="C#" Value="public class VolumePolicyInfo : Microsoft.WindowsAzure.Management.StorSimple.Models.CisBaseObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VolumePolicyInfo extends Microsoft.WindowsAzure.Management.StorSimple.Models.CisBaseObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class VolumePolicyInfo&#xA;Inherits CisBaseObject" />
  <TypeSignature Language="F#" Value="type VolumePolicyInfo = class&#xA;    inherit CisBaseObject" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Management.StorSimple.Models.CisBaseObject</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            このクラスは、ボリュームに関連付けられたポリシーを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolumePolicyInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VolumePolicyInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AssociatedBackupPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AssociatedBackupPolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AssociatedBackupPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo.AssociatedBackupPolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property AssociatedBackupPolicies As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AssociatedBackupPolicies : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo.AssociatedBackupPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 このボリュームに関連付けられているバックアップ ポリシー。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataContainerId">
      <MemberSignature Language="C#" Value="public string DataContainerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo.DataContainerId" />
      <MemberSignature Language="VB.NET" Value="Public Property DataContainerId As String" />
      <MemberSignature Language="F#" Value="member this.DataContainerId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo.DataContainerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 このボリュームのデータ コンテナーの識別子。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataContainerName">
      <MemberSignature Language="C#" Value="public string DataContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo.DataContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property DataContainerName As String" />
      <MemberSignature Language="F#" Value="member this.DataContainerName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo.DataContainerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 このボリュームのデータ コンテナーの名前。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>