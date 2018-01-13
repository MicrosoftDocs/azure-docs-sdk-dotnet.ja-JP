<Type Name="CheckNameAvailabilityResultInner" FullName="Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityResultInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityResultInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityResultInner" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityResultInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            CheckNameAvailability 操作の応答。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResultInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CheckNameAvailabilityResultInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResultInner (Nullable&lt;bool&gt; nameAvailable = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Reason&gt; reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; nameAvailable, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Reason&gt; reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner.#ctor(System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.Reason},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As Nullable(Of Reason) = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner : Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Reason&gt; * string -&gt; Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner" Usage="new Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner (nameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Reason&gt;" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameAvailable">名前が使用するために使用できるかどうかを示すブール値を取得します。 True の場合、名前は使用可能なです。 False の場合、名前は既に取得されて有効ではありませんやは使用できません。</param>
        <param name="reason">ストレージ アカウント名を使用できませんでした理由を取得します。 Reason 要素は NameAvailable が false の場合にのみ返されます。 使用可能な値が含まれます: 'AccountNameInvalid'、'に対する'</param>
        <param name="message">さらに詳しく理由の値を示すエラー メッセージを取得します。</param>
        <summary>
            CheckNameAvailabilityResultInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            さらに詳しく理由の値を示すエラー メッセージを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            名前が使用するために使用できるかどうかを示すブール値を取得します。 True の場合、名前は使用可能なです。 False の場合、名前は既に取得されて有効ではありませんやは使用できません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Reason&gt; Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Reason&gt; Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As Nullable(Of Reason)" />
      <MemberSignature Language="F#" Value="member this.Reason : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Reason&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Reason&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウント名を使用できませんでした理由を取得します。 Reason 要素は NameAvailable が false の場合にのみ返されます。 使用可能な値が含まれます: 'AccountNameInvalid'、'に対する'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>