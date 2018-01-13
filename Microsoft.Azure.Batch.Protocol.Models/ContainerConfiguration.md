<Type Name="ContainerConfiguration" FullName="Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration">
  <TypeSignature Language="C#" Value="public class ContainerConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi ContainerConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerConfiguration" />
  <TypeSignature Language="F#" Value="type ContainerConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            コンテナーが有効なプールの構成。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ContainerConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerConfiguration (System.Collections.Generic.IList&lt;string&gt; containerImageNames = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt; containerRegistries = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; containerImageNames, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt; containerRegistries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional containerImageNames As IList(Of String) = null, Optional containerRegistries As IList(Of ContainerRegistry) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration" Usage="new Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration (containerImageNames, containerRegistries)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="containerImageNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="containerRegistries" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt;" />
      </Parameters>
      <Docs>
        <param name="containerImageNames">コンテナー イメージ名のコレクション。</param>
        <param name="containerRegistries">追加のプライベート レジストリのコンテナーをプルできます。</param>
        <summary>
            ContainerConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerImageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ContainerImageNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ContainerImageNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.ContainerImageNames" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerImageNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ContainerImageNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.ContainerImageNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerImageNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナーのイメージ名のコレクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            これが"docker pull"に指定された完全なイメージの参照です。 イメージが代替のレジストリで完全修飾されていない限り、既定の Docker レジストリからイメージが供給されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRegistries">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt; ContainerRegistries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt; ContainerRegistries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.ContainerRegistries" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRegistries As IList(Of ContainerRegistry)" />
      <MemberSignature Language="F#" Value="member this.ContainerRegistries : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.ContainerRegistries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerRegistries")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナーをプルする追加のプライベート レジストリを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            資格情報を必要とするプライベート レジストリからイメージをダウンロードする必要がある場合は、そのそれらの資格情報をここで提供する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public static string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.Type" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>