<Type Name="Updates" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Updates">
  <TypeSignature Language="C#" Value="public class Updates : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Updates extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates" />
  <TypeSignature Language="VB.NET" Value="Public Class Updates&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type Updates = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            デバイスの更新プログラムのプロファイル。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Updates ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            更新プログラムのクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Updates (string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;bool&gt; regularUpdatesAvailable = null, Nullable&lt;bool&gt; maintenanceModeUpdatesAvailable = null, Nullable&lt;bool&gt; isUpdateInProgress = null, Nullable&lt;DateTime&gt; lastUpdatedTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;bool&gt; regularUpdatesAvailable, valuetype System.Nullable`1&lt;bool&gt; maintenanceModeUpdatesAvailable, valuetype System.Nullable`1&lt;bool&gt; isUpdateInProgress, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.#ctor(System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional regularUpdatesAvailable As Nullable(Of Boolean) = null, Optional maintenanceModeUpdatesAvailable As Nullable(Of Boolean) = null, Optional isUpdateInProgress As Nullable(Of Boolean) = null, Optional lastUpdatedTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Updates : string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Updates" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Updates (id, name, type, kind, regularUpdatesAvailable, maintenanceModeUpdatesAvailable, isUpdateInProgress, lastUpdatedTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="regularUpdatesAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="maintenanceModeUpdatesAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isUpdateInProgress" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="lastUpdatedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id">オブジェクトを一意に識別するパス ID です。</param>
        <param name="name">オブジェクトの名前。</param>
        <param name="type">オブジェクトの階層型です。</param>
        <param name="kind">オブジェクトの種類。 現在は Series8000 はサポートされています。 使用可能な値が含まれます: 'Series8000'</param>
        <param name="regularUpdatesAvailable">通常の更新プログラムがデバイスの使用可能な場合は 'true' に設定されます。</param>
        <param name="maintenanceModeUpdatesAvailable">メンテナンス モードを使用可能な更新の場合は 'true' に設定します。</param>
        <param name="isUpdateInProgress">かどうか、更新が進行中かを示します。</param>
        <param name="lastUpdatedTime">前回の更新が完了した時刻。</param>
        <summary>
            更新プログラムのクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsUpdateInProgress">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsUpdateInProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsUpdateInProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.IsUpdateInProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property IsUpdateInProgress As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsUpdateInProgress : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.IsUpdateInProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isUpdateInProgress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定するかどうか、更新が進行中かを示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastUpdatedTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastUpdatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.LastUpdatedTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastUpdatedTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.LastUpdatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastUpdatedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または前回の更新が完了したときに時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaintenanceModeUpdatesAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; MaintenanceModeUpdatesAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; MaintenanceModeUpdatesAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.MaintenanceModeUpdatesAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property MaintenanceModeUpdatesAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.MaintenanceModeUpdatesAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.MaintenanceModeUpdatesAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maintenanceModeUpdatesAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定可能な更新がメンテナンス モードの場合は 'true' に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegularUpdatesAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RegularUpdatesAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RegularUpdatesAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.RegularUpdatesAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property RegularUpdatesAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RegularUpdatesAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Updates.RegularUpdatesAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.regularUpdatesAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または通常の更新プログラムがデバイスの使用可能な場合に、'true' に設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>