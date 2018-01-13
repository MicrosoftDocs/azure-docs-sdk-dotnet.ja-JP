<Type Name="ContainerServiceAgentPoolProfile" FullName="Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile">
  <TypeSignature Language="C#" Value="public class ContainerServiceAgentPoolProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceAgentPoolProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceAgentPoolProfile" />
  <TypeSignature Language="F#" Value="type ContainerServiceAgentPoolProfile = class" />
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
            コンテナー サービスのエージェント プールのプロファイル。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceAgentPoolProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.#ctor" />
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
            ContainerServiceAgentPoolProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceAgentPoolProfile (string name, int count, string vmSize, string dnsPrefix, string fqdn = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, int32 count, string vmSize, string dnsPrefix, string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.#ctor(System.String,System.Int32,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, count As Integer, vmSize As String, dnsPrefix As String, Optional fqdn As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile : string * int * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile" Usage="new Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile (name, count, vmSize, dnsPrefix, fqdn)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="dnsPrefix" Type="System.String" />
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">サブスクリプションとリソース グループのコンテキストでは、エージェント プール プロファイルの一意の名前。</param>
        <param name="count">Docker コンテナーのホストにエージェント (Vm) の数。 有効な値は、1 ~ 100 (包括) の範囲でなければなりません。 既定値は 1 です。 </param>
        <param name="vmSize">エージェントの Vm のサイズです。 使用可能な値が含まれます: 'Standard_A0'、'Standard_A1'、'Standard_A2'、'Standard_A3'、'Standard_A4'、'Standard_A5'、'Standard_A6'、'Standard_A7'、'Standard_A8'、'Standard_A9'、'Standard_A10'、'Standard_A11'、'Standard_D1'、'Standard_D2'、'Standard_D3'、'Standard_D4'、'Standard_D11'、'Standard_D12'、'Standard_D13'、'Standard_D14'、'Standard_D1_v2'、'Standard_D2_v2'、'Standard_D3_v2'、'Standard_D4_v2'、'Standard_D5_v2'、'Standard_D11_v2'、'Standard_D12_v2'、'Standard_D13_v2'、'Standard_D14_v2'、'Standard_G1'、'Standard_G2'、'Standard_G3'、'Standard_G4'、'Standard_G5'、'Standard_DS1'、'Standard_DS2'、'Standard_DS3'、'Standard_DS4'、'Standard_DS11'、'Standard_DS12'、'Standard_DS13'、'Standard_DS14'、' Standard_GS1'、'Standard_GS2'、'Standard_GS3'、'Standard_GS4'、'Standard_GS5'</param>
        <param name="dnsPrefix">エージェント プールに対応する FQDN を作成するために使用する DNS プレフィックスです。</param>
        <param name="fqdn">エージェント プールの fdqn のサンプルです。</param>
        <summary>
            ContainerServiceAgentPoolProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または docker コンテナーのホストにエージェント (Vm) の数を設定します。
            有効な値は、1 ~ 100 (包括) の範囲でなければなりません。 既定値は 1 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsPrefix">
      <MemberSignature Language="C#" Value="public string DnsPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.DnsPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsPrefix As String" />
      <MemberSignature Language="F#" Value="member this.DnsPrefix : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.DnsPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dnsPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエージェント プールに対応する FQDN を作成するために使用する DNS プレフィックスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fqdn">
      <MemberSignature Language="C#" Value="public string Fqdn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Fqdn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Fqdn As String" />
      <MemberSignature Language="F#" Value="member this.Fqdn : string" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Fqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fqdn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エージェント プールの fdqn のサンプルを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブスクリプションとリソース グループのコンテキストでは、エージェント プール プロファイルの一意の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceAgentPoolProfile.Validate " />
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
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエージェント Vm のサイズを設定します。 使用可能な値が含まれます: 'Standard_A0'、'Standard_A1'、'Standard_A2'、'Standard_A3'、'Standard_A4'、'Standard_A5'、'Standard_A6'、'Standard_A7'、'Standard_A8'、'Standard_A9'、'Standard_A10'、'Standard_A11'、'Standard_D1'、'Standard_D2'、'Standard_D3'、'Standard_D4'、'Standard_D11'、'Standard_D12'、'Standard_D13'、'Standard_D14'、'Standard_D1_v2'、'Standard_D2_v2'、'Standard_D3_v2'、'Standard_D4_v2'、'Standard_D5_v2'、'Standard_D11_v2'、'Standard_D12_v2'、'Standard_D13_v2'、'Standard_D14_v2'、'Standard_G1'、'Standard_G2'、'Standard_G3'、'Standard_G4'、'Standard_G5'、'Standard_DS1'、'Standard_DS2'、'Standard_DS3'、'Standard_DS4'、'Standard_DS11'、'Standard_DS12'、'Standard_DS13'、'Standard_DS14'、' Standard_GS1'、'Standard_GS2'、'Standard_GS3'、'Standard_GS4'、'Standard_GS5'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>