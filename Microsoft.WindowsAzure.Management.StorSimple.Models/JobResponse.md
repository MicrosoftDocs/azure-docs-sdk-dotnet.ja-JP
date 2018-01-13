<Type Name="JobResponse" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse">
  <TypeSignature Language="C#" Value="public class JobResponse : Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobResponse extends Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class JobResponse&#xA;Inherits AzureOperationResponse" />
  <TypeSignature Language="F#" Value="type JobResponse = class&#xA;    inherit AzureOperationResponse" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.AzureOperationResponse</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            JobResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobResponse (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse : string -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse jobId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId">To be added.</param>
        <summary>
            必須の引数で JobResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse.JobId" />
      <MemberSignature Language="VB.NET" Value="Public Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse.JobId" />
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
            必須。 送信されたデバイスのジョブのジョブ Id
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>