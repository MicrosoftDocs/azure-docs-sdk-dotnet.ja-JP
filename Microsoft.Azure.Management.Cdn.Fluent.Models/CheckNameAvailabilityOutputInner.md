<Type Name="CheckNameAvailabilityOutputInner" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityOutputInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityOutputInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityOutputInner" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityOutputInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityOutputInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CheckNameAvailabilityOutputInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityOutputInner (Nullable&lt;bool&gt; nameAvailable = null, string reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; nameAvailable, string reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner.#ctor(System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner : Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner (nameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameAvailable">名前が使用できるかどうかを示します。</param>
        <param name="reason">名前が使用可能な理由です。</param>
        <param name="message">名前を使用できない原因を説明する詳細なエラー メッセージ。</param>
        <summary>
            CheckNameAvailabilityOutputInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
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
            取得または設定の名前を使用できない原因を説明する詳細なエラー メッセージ。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
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
            取得または設定は、名前が使用できるかどうかを示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner.Reason" />
      <MemberSignature Language="VB.NET" Value="Public Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CheckNameAvailabilityOutputInner.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            取得または名前が使用可能な理由を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>