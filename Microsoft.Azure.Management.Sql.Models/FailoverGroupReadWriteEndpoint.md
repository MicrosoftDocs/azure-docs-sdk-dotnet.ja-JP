<Type Name="FailoverGroupReadWriteEndpoint" FullName="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint">
  <TypeSignature Language="C#" Value="public class FailoverGroupReadWriteEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FailoverGroupReadWriteEndpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverGroupReadWriteEndpoint" />
  <TypeSignature Language="F#" Value="type FailoverGroupReadWriteEndpoint = class" />
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
            フェールオーバー グループ インスタンスのエンドポイントを読み取り/書き込みです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroupReadWriteEndpoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            FailoverGroupReadWriteEndpoint クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroupReadWriteEndpoint (string failoverPolicy, Nullable&lt;int&gt; failoverWithDataLossGracePeriodMinutes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string failoverPolicy, valuetype System.Nullable`1&lt;int32&gt; failoverWithDataLossGracePeriodMinutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (failoverPolicy As String, Optional failoverWithDataLossGracePeriodMinutes As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint" Usage="new Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint (failoverPolicy, failoverWithDataLossGracePeriodMinutes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="failoverPolicy" Type="System.String" />
        <Parameter Name="failoverWithDataLossGracePeriodMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="failoverPolicy">グループのフェールオーバーの読み取り/書き込みエンドポイントのフェールオーバー ポリシー。 FailoverPolicy が自動である場合 failoverWithDataLossGracePeriodMinutes が必要です。 使用可能な値が含まれます: 'Manual'、'Automatic'</param>
        <param name="failoverWithDataLossGracePeriodMinutes">読み取り/書き込みのエンドポイントのデータの損失をフェールオーバーする前に猶予期間が試行されます。 FailoverPolicy が自動である場合 failoverWithDataLossGracePeriodMinutes が必要です。</param>
        <summary>
            FailoverGroupReadWriteEndpoint クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverPolicy">
      <MemberSignature Language="C#" Value="public string FailoverPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailoverPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.FailoverPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property FailoverPolicy As String" />
      <MemberSignature Language="F#" Value="member this.FailoverPolicy : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.FailoverPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failoverPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフェールオーバー グループの読み取り/書き込みのエンドポイントのフェールオーバー ポリシーを設定します。 FailoverPolicy が自動である場合 failoverWithDataLossGracePeriodMinutes が必要です。 使用可能な値が含まれます: 'Manual'、'Automatic'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverWithDataLossGracePeriodMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FailoverWithDataLossGracePeriodMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FailoverWithDataLossGracePeriodMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.FailoverWithDataLossGracePeriodMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property FailoverWithDataLossGracePeriodMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FailoverWithDataLossGracePeriodMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.FailoverWithDataLossGracePeriodMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failoverWithDataLossGracePeriodMinutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または読み取り/書き込みエンドポイントのデータ損失のフェールオーバーが試行する前に猶予期間を設定します。 FailoverPolicy が自動である場合 failoverWithDataLossGracePeriodMinutes が必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="failoverGroupReadWriteEndpoint.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>