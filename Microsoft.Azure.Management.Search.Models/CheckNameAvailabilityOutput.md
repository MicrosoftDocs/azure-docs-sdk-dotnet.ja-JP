<Type Name="CheckNameAvailabilityOutput" FullName="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityOutput" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityOutput extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityOutput" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityOutput = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            名前の可用性をチェック API の出力です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityOutput ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CheckNameAvailabilityOutput クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityOutput (Nullable&lt;bool&gt; isNameAvailable = null, string reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; isNameAvailable, string reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.#ctor(System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional isNameAvailable As Nullable(Of Boolean) = null, Optional reason As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput : Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput" Usage="new Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput (isNameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isNameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="isNameAvailable">名前が使用できるかどうかを示す値。</param>
        <param name="reason">名前が使用可能な理由です。
            '無効' に示すは、指定された名前が (長さが無効、サポートされていない文字など) の名前付けに関する要件と一致しません。
            'に対する' は、名前が既に使用されて、にないため、使用可能なことを示します。 使用可能な値が含まれます: '無効'、'に対する'</param>
        <param name="message">名前の正しくない理由と、そのリソースの名前付けに関する要件を説明するメッセージ。 使用可能な '無効' 場合にのみが返されます 'reason' プロパティにします。</param>
        <summary>
            CheckNameAvailabilityOutput クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsNameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsNameAvailable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsNameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.IsNameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsNameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsNameAvailable : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.IsNameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nameAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            名前が使用できるかどうかを示す値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
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
            名前の正しくない理由と、そのリソースの名前付けに関する要件を説明するメッセージを取得します。 使用可能な '無効' 場合にのみが返されます 'reason' プロパティにします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string" Usage="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            名前が使用可能な理由を取得します。 '無効' に示すは、指定された名前が (長さが無効、サポートされていない文字など) の名前付けに関する要件と一致しません。 'に対する' は、名前が既に使用されて、にないため、使用可能なことを示します。 使用可能な値が含まれます: '無効'、'に対する'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>