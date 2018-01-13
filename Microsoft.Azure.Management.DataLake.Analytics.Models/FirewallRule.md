<Type Name="FirewallRule" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule">
  <TypeSignature Language="C#" Value="public class FirewallRule : Microsoft.Azure.Management.DataLake.Analytics.Models.OptionalSubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FirewallRule extends Microsoft.Azure.Management.DataLake.Analytics.Models.OptionalSubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule" />
  <TypeSignature Language="VB.NET" Value="Public Class FirewallRule&#xA;Inherits OptionalSubResource" />
  <TypeSignature Language="F#" Value="type FirewallRule = class&#xA;    inherit OptionalSubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.OptionalSubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Data Lake Analytics ファイアウォール規則の情報
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FirewallRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            FirewallRule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FirewallRule (string startIpAddress, string endIpAddress, string id = null, string name = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string startIpAddress, string endIpAddress, string id, string name, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startIpAddress As String, endIpAddress As String, Optional id As String = null, Optional name As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule : string * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule (startIpAddress, endIpAddress, id, name, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startIpAddress" Type="System.String" />
        <Parameter Name="endIpAddress" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIpAddress">ファイアウォール ルールの開始 IP アドレス。 Ipv4 または ipv6 のいずれかを指定できます。 始点と終点が同じプロトコルでなければなりません。</param>
        <param name="endIpAddress">ファイアウォール規則の終了 IP アドレス。 Ipv4 または ipv6 のいずれかを指定できます。 始点と終点が同じプロトコルでなければなりません。</param>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <summary>
            FirewallRule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndIpAddress">
      <MemberSignature Language="C#" Value="public string EndIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.EndIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EndIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndIpAddress : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.EndIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイアウォール ルールの終了 IP アドレスを設定します。 Ipv4 または ipv6 のいずれかを指定できます。 始点と終点が同じプロトコルでなければなりません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIpAddress">
      <MemberSignature Language="C#" Value="public string StartIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.StartIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property StartIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.StartIpAddress : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.StartIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイアウォール ルールの開始 IP アドレスを設定します。 Ipv4 または ipv6 のいずれかを指定できます。 始点と終点が同じプロトコルでなければなりません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="firewallRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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