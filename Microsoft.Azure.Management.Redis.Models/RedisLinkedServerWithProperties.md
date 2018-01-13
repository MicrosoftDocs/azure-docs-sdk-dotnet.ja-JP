<Type Name="RedisLinkedServerWithProperties" FullName="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties">
  <TypeSignature Language="C#" Value="public class RedisLinkedServerWithProperties : Microsoft.Azure.Management.Redis.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisLinkedServerWithProperties extends Microsoft.Azure.Management.Redis.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisLinkedServerWithProperties&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type RedisLinkedServerWithProperties = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Redis.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Put または get にリンク サーバー (プロパティ) を持つ Redis cache の応答です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisLinkedServerWithProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RedisLinkedServerWithProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisLinkedServerWithProperties (string linkedRedisCacheId, string linkedRedisCacheLocation, Microsoft.Azure.Management.Redis.Models.ReplicationRole serverRole, string id = null, string name = null, string type = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string linkedRedisCacheId, string linkedRedisCacheLocation, valuetype Microsoft.Azure.Management.Redis.Models.ReplicationRole serverRole, string id, string name, string type, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.#ctor(System.String,System.String,Microsoft.Azure.Management.Redis.Models.ReplicationRole,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedRedisCacheId As String, linkedRedisCacheLocation As String, serverRole As ReplicationRole, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties : string * string * Microsoft.Azure.Management.Redis.Models.ReplicationRole * string * string * string * string -&gt; Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties" Usage="new Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties (linkedRedisCacheId, linkedRedisCacheLocation, serverRole, id, name, type, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedRedisCacheId" Type="System.String" />
        <Parameter Name="linkedRedisCacheLocation" Type="System.String" />
        <Parameter Name="serverRole" Type="Microsoft.Azure.Management.Redis.Models.ReplicationRole" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="linkedRedisCacheId">リンク redis cache の完全修飾リソース Id。</param>
        <param name="linkedRedisCacheLocation">リンクされた redis キャッシュの場所です。</param>
        <param name="serverRole">リンク サーバーの役割。 使用可能な値が含まれます 'Primary'、'セカンダリ'。</param>
        <param name="id">リソースの ID</param>
        <param name="name">リソース名。</param>
        <param name="type">リソースの種類。</param>
        <param name="provisioningState">プライマリとセカンダリの間のリンクのターミナル状態は redis キャッシュです。</param>
        <summary>
            RedisLinkedServerWithProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedRedisCacheId">
      <MemberSignature Language="C#" Value="public string LinkedRedisCacheId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedRedisCacheId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.LinkedRedisCacheId" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedRedisCacheId As String" />
      <MemberSignature Language="F#" Value="member this.LinkedRedisCacheId : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.LinkedRedisCacheId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linkedRedisCacheId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリンクされた redis cache の完全修飾リソース Id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedRedisCacheLocation">
      <MemberSignature Language="C#" Value="public string LinkedRedisCacheLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedRedisCacheLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.LinkedRedisCacheLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedRedisCacheLocation As String" />
      <MemberSignature Language="F#" Value="member this.LinkedRedisCacheLocation : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.LinkedRedisCacheLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linkedRedisCacheLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリンクされた redis キャッシュの場所を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プライマリとセカンダリの redis キャッシュの間のリンクのターミナル状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerRole">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Models.ReplicationRole ServerRole { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Redis.Models.ReplicationRole ServerRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.ServerRole" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerRole As ReplicationRole" />
      <MemberSignature Language="F#" Value="member this.ServerRole : Microsoft.Azure.Management.Redis.Models.ReplicationRole with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.ServerRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverRole")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.ReplicationRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリンク サーバーの役割を設定します。 使用可能な値が含まれます 'Primary'、'セカンダリ'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerWithProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redisLinkedServerWithProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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