<Type Name="ReplicationLinkInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner">
  <TypeSignature Language="C#" Value="public class ReplicationLinkInner : Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReplicationLinkInner extends Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ReplicationLinkInner&#xA;Inherits SqlSubResource" />
  <TypeSignature Language="F#" Value="type ReplicationLinkInner = class&#xA;    inherit SqlSubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure SQL データベース レプリケーション リンクを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicationLinkInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ReplicationLinkInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicationLinkInner (string name = null, string id = null, string partnerServer = null, string partnerDatabase = null, string partnerLocation = null, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; role = null, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; partnerRole = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;int&gt; percentComplete = null, string replicationState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, string partnerServer, string partnerDatabase, string partnerLocation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; role, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; partnerRole, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;int32&gt; percentComplete, string replicationState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole},System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole},System.Nullable{System.DateTime},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional id As String = null, Optional partnerServer As String = null, Optional partnerDatabase As String = null, Optional partnerLocation As String = null, Optional role As Nullable(Of ReplicationRole) = null, Optional partnerRole As Nullable(Of ReplicationRole) = null, Optional startTime As Nullable(Of DateTime) = null, Optional percentComplete As Nullable(Of Integer) = null, Optional replicationState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner : string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner (name, id, partnerServer, partnerDatabase, partnerLocation, role, partnerRole, startTime, percentComplete, replicationState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="partnerServer" Type="System.String" />
        <Parameter Name="partnerDatabase" Type="System.String" />
        <Parameter Name="partnerLocation" Type="System.String" />
        <Parameter Name="role" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt;" />
        <Parameter Name="partnerRole" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="percentComplete" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="replicationState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">リソース名</param>
        <param name="id">リソース id です。</param>
        <param name="partnerServer">Azure SQL データベースのパートナーをホストする Azure の SQL server の名前。</param>
        <param name="partnerDatabase">Azure SQL データベースのパートナーの名前。</param>
        <param name="partnerLocation">Azure SQL データベースのパートナーの Azure 地域。</param>
        <param name="role">レプリケーション リンクに、Azure SQL データベースのロール。 使用可能な値が含まれます 'Primary'、'セカンダリ'、'NonReadableSecondary'、'Source'、[コピー]。</param>
        <param name="partnerRole">Azure SQL データベース レプリケーション リンクに、パートナーのロール。 使用可能な値が含まれます 'Primary'、'セカンダリ'、'NonReadableSecondary'、'Source'、[コピー]。</param>
        <param name="startTime">レプリケーション リンク (ISO8601 形式) の開始時刻です。</param>
        <param name="percentComplete">レプリケーション リンクの完全なシード処理の割合。</param>
        <param name="replicationState">レプリケーション リンクのレプリケーションの状態。 使用可能な値が含まれます: 'PENDING'、'シード処理'、'CATCH_UP'、'中断'</param>
        <summary>
            ReplicationLinkInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerDatabase">
      <MemberSignature Language="C#" Value="public string PartnerDatabase { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerDatabase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerDatabase" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerDatabase As String" />
      <MemberSignature Language="F#" Value="member this.PartnerDatabase : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerDatabase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerDatabase")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure SQL データベースのパートナーの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerLocation">
      <MemberSignature Language="C#" Value="public string PartnerLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerLocation As String" />
      <MemberSignature Language="F#" Value="member this.PartnerLocation : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure SQL データベースのパートナーの Azure リージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerRole">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; PartnerRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; PartnerRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerRole As Nullable(Of ReplicationRole)" />
      <MemberSignature Language="F#" Value="member this.PartnerRole : Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerRole")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure SQL データベース レプリケーション リンクに、パートナーのロールを取得します。 使用可能な値が含まれます 'Primary'、'セカンダリ'、'NonReadableSecondary'、'Source'、[コピー]。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerServer">
      <MemberSignature Language="C#" Value="public string PartnerServer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerServer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerServer As String" />
      <MemberSignature Language="F#" Value="member this.PartnerServer : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure SQL データベースのパートナーをホストする Azure の SQL server の名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.percentComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリケーション リンクの完全なシード処理の割合を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationState">
      <MemberSignature Language="C#" Value="public string ReplicationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.ReplicationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationState As String" />
      <MemberSignature Language="F#" Value="member this.ReplicationState : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.ReplicationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replicationState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリケーション リンクのレプリケーション状態を取得します。 使用可能な値が含まれます: 'PENDING'、'シード処理'、'CATCH_UP'、'中断'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Role">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; Role { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; Role" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.Role" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Role As Nullable(Of ReplicationRole)" />
      <MemberSignature Language="F#" Value="member this.Role : Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.Role" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.role")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリケーション リンクに、Azure SQL データベースの役割を取得します。
            使用可能な値が含まれます 'Primary'、'セカンダリ'、'NonReadableSecondary'、'Source'、[コピー]。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリケーション リンク (ISO8601 形式) の開始時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>