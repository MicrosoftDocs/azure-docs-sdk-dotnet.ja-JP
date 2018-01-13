<Type Name="Operation" FullName="Microsoft.Azure.Management.WebSites.Models.Operation">
  <TypeSignature Language="C#" Value="public class Operation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Operation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.Operation" />
  <TypeSignature Language="VB.NET" Value="Public Class Operation" />
  <TypeSignature Language="F#" Value="type Operation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            操作。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Operation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Operation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation (string id = null, string name = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt; status = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt; errors = null, Nullable&lt;DateTime&gt; createdTime = null, Nullable&lt;DateTime&gt; modifiedTime = null, Nullable&lt;DateTime&gt; expirationTime = null, Nullable&lt;Guid&gt; geoMasterOperationId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt; status, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt; errors, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; modifiedTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expirationTime, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; geoMasterOperationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Operation.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.OperationStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.ErrorEntity},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional status As Nullable(Of OperationStatus) = null, Optional errors As IList(Of ErrorEntity) = null, Optional createdTime As Nullable(Of DateTime) = null, Optional modifiedTime As Nullable(Of DateTime) = null, Optional expirationTime As Nullable(Of DateTime) = null, Optional geoMasterOperationId As Nullable(Of Guid) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.Operation : string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Guid&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.Operation" Usage="new Microsoft.Azure.Management.WebSites.Models.Operation (id, name, status, errors, createdTime, modifiedTime, expirationTime, geoMasterOperationId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt;" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt;" />
        <Parameter Name="createdTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="modifiedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="geoMasterOperationId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="id">操作 ID</param>
        <param name="name">操作の名前。</param>
        <param name="status">操作の現在の状態。 使用可能な値が含まれます: '処理中'、'失敗'、'成功'、'TimedOut'、'作成済み</param>
        <param name="errors">すべてのエラーは、操作に関連付けます。</param>
        <param name="createdTime">操作が開始された時刻。</param>
        <param name="modifiedTime">操作が更新されたときの時刻。</param>
        <param name="expirationTime">操作の期限が切れる時刻。</param>
        <param name="geoMasterOperationId">操作 id のスタンプに対してのみ適用できます。</param>
        <summary>
            Operation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Operation.CreatedTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Operation.CreatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createdTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または操作が開始された時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt; Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Operation.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of ErrorEntity)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Operation.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または任意のエラーに関連付け、操作を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Operation.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Operation.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または操作の期限が切れる時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoMasterOperationId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; GeoMasterOperationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; GeoMasterOperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Operation.GeoMasterOperationId" />
      <MemberSignature Language="VB.NET" Value="Public Property GeoMasterOperationId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.GeoMasterOperationId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Operation.GeoMasterOperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="geoMasterOperationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定スタンプ操作 id にのみ適用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Operation.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Operation.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定操作 id です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ModifiedTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Operation.ModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ModifiedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ModifiedTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Operation.ModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="modifiedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または操作が更新された日時を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Operation.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Operation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
            取得または操作の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Operation.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of OperationStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Operation.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または操作の現在の状態を設定します。 使用可能な値が含まれます: '処理中'、'失敗'、'成功'、'TimedOut'、'作成済み
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>