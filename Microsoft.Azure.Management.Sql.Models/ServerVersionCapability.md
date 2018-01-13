<Type Name="ServerVersionCapability" FullName="Microsoft.Azure.Management.Sql.Models.ServerVersionCapability">
  <TypeSignature Language="C#" Value="public class ServerVersionCapability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServerVersionCapability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability" />
  <TypeSignature Language="VB.NET" Value="Public Class ServerVersionCapability" />
  <TypeSignature Language="F#" Value="type ServerVersionCapability = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            サーバーの機能です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerVersionCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ServerVersionCapability クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerVersionCapability (string name = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.EditionCapability&gt; supportedEditions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt; supportedElasticPoolEditions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.EditionCapability&gt; supportedEditions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt; supportedElasticPoolEditions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.CapabilityStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.EditionCapability},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional status As Nullable(Of CapabilityStatus) = null, Optional supportedEditions As IList(Of EditionCapability) = null, Optional supportedElasticPoolEditions As IList(Of ElasticPoolEditionCapability) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ServerVersionCapability : string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.EditionCapability&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ServerVersionCapability" Usage="new Microsoft.Azure.Management.Sql.Models.ServerVersionCapability (name, status, supportedEditions, supportedElasticPoolEditions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" />
        <Parameter Name="supportedEditions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.EditionCapability&gt;" />
        <Parameter Name="supportedElasticPoolEditions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt;" />
      </Parameters>
      <Docs>
        <param name="name">サーバーのバージョン名。</param>
        <param name="status">サーバーのバージョンの状態です。 使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</param>
        <param name="supportedEditions">サポートされるデータベース エディションの一覧。</param>
        <param name="supportedElasticPoolEditions">サポートされている弾力性プールの各エディションの一覧。</param>
        <summary>
            ServerVersionCapability クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            サーバーのバージョンの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CapabilityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サーバーのバージョンの状態を取得します。 使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedEditions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.EditionCapability&gt; SupportedEditions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.EditionCapability&gt; SupportedEditions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.SupportedEditions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedEditions As IList(Of EditionCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedEditions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.EditionCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.SupportedEditions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedEditions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.EditionCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サポートされるデータベース エディションの一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedElasticPoolEditions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt; SupportedElasticPoolEditions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt; SupportedElasticPoolEditions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.SupportedElasticPoolEditions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedElasticPoolEditions As IList(Of ElasticPoolEditionCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedElasticPoolEditions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.SupportedElasticPoolEditions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedElasticPoolEditions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サポートされている弾力性プールのエディションの一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>