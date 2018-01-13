<Type Name="BatchAccountCreateHeadersInner" FullName="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateHeadersInner">
  <TypeSignature Language="C#" Value="public class BatchAccountCreateHeadersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchAccountCreateHeadersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateHeadersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchAccountCreateHeadersInner" />
  <TypeSignature Language="F#" Value="type BatchAccountCreateHeadersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            作成操作のヘッダーを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountCreateHeadersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateHeadersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BatchAccountCreateHeadersInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountCreateHeadersInner (string location = null, Nullable&lt;int&gt; retryAfter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, valuetype System.Nullable`1&lt;int32&gt; retryAfter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateHeadersInner.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional retryAfter As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateHeadersInner : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateHeadersInner" Usage="new Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateHeadersInner (location, retryAfter)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="retryAfter" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="location">非同期操作の状態を確認するために使用されたリソースの URL です。</param>
        <param name="retryAfter">非同期操作の状態を確認するための推奨されています。 値は、秒を表す整数です。</param>
        <summary>
            BatchAccountCreateHeadersInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateHeadersInner.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateHeadersInner.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または非同期操作の状態を確認するために使用されたリソースの URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryAfter">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetryAfter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetryAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateHeadersInner.RetryAfter" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryAfter As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetryAfter : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateHeadersInner.RetryAfter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Retry-After")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または非同期操作の状態を確認する推奨の遅延を設定します。 値は、秒を表す整数です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>