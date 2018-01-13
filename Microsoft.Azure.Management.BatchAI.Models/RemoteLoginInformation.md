<Type Name="RemoteLoginInformation" FullName="Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation">
  <TypeSignature Language="C#" Value="public class RemoteLoginInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RemoteLoginInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class RemoteLoginInformation" />
  <TypeSignature Language="F#" Value="type RemoteLoginInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クラスター内のコンピューティング ノードに SSH/RDP にリモート ログインの詳細が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteLoginInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RemoteLoginInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteLoginInformation (string nodeId, string ipAddress, double port);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeId, string ipAddress, float64 port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.#ctor(System.String,System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeId As String, ipAddress As String, port As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation : string * string * double -&gt; Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation" Usage="new Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation (nodeId, ipAddress, port)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="ipAddress" Type="System.String" />
        <Parameter Name="port" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="nodeId">コンピューティング ノードの id。</param>
        <param name="ipAddress">ip アドレス</param>
        <param name="port">ポート番号</param>
        <summary>
            RemoteLoginInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddress">
      <MemberSignature Language="C#" Value="public string IpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.IpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddress As String" />
      <MemberSignature Language="F#" Value="member this.IpAddress : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.IpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ip アドレス取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public string NodeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeId As String" />
      <MemberSignature Language="F#" Value="member this.NodeId : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードの id を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public double Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Double" />
      <MemberSignature Language="F#" Value="member this.Port : double with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはポート番号を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="remoteLoginInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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