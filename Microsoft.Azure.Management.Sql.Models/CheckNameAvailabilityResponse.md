<Type Name="CheckNameAvailabilityResponse" FullName="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityResponse" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityResponse = class" />
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
            リソースの指定された名前が使用できるかどうかを示す応答です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CheckNameAvailabilityResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResponse (Nullable&lt;bool&gt; available = null, string message = null, string name = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt; reason = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; available, string message, string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt; reason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.#ctor(System.Nullable{System.Boolean},System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional available As Nullable(Of Boolean) = null, Optional message As String = null, Optional name As String = null, Optional reason As Nullable(Of CheckNameAvailabilityReason) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse : Nullable&lt;bool&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt; -&gt; Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse" Usage="new Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse (available, message, name, reason)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="available" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="reason" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt;" />
      </Parameters>
      <Docs>
        <param name="available">True の場合は、名前は、使用可能なそれ以外の場合は false。</param>
        <param name="message">名前が使用可能な理由を説明するメッセージ。 名前が使用可能な場合は null になります。</param>
        <param name="name">可用性がチェックされた名前です。</param>
        <param name="reason">名前が使用可能な理由を説明する理由コード。 名前が使用可能な場合は null になります。 使用可能な値が含まれます: '無効'、'に対する'</param>
        <summary>
            CheckNameAvailabilityResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Available">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Available { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Available" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Available" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Available As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Available : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Available" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="available")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            True の場合は、名前は、使用可能なそれ以外の場合は false を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            名前が使用可能な理由を説明するメッセージを取得します。 名前が使用可能な場合は null になります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Name" />
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
            可用性がチェックされた名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt; Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt; Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As Nullable(Of CheckNameAvailabilityReason)" />
      <MemberSignature Language="F#" Value="member this.Reason : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt;" Usage="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityReason&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            名前が使用可能な理由を説明する理由コードを取得します。 名前が使用可能な場合は null になります。 使用可能な値が含まれます: '無効'、'に対する'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>