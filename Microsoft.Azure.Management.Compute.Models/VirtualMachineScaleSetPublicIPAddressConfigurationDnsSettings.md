<Type Name="VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシン スケール セット ネットワーク構成の DNS 設定をについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings (string domainNameLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string domainNameLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (domainNameLabel As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings : string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings domainNameLabel" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="domainNameLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domainNameLabel">ドメイン名ラベルにします。ドメイン名ラベルと vm インデックスの連結が作成される PublicIPAddress リソースのドメイン名ラベルになります</param>
        <summary>
            VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainNameLabel">
      <MemberSignature Language="C#" Value="public string DomainNameLabel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainNameLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings.DomainNameLabel" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainNameLabel As String" />
      <MemberSignature Language="F#" Value="member this.DomainNameLabel : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings.DomainNameLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="domainNameLabel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはドメイン名ラベルを設定します。ドメイン名ラベルと vm インデックスの連結が作成される PublicIPAddress リソースのドメイン名ラベルになります
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetPublicIPAddressConfigurationDnsSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>