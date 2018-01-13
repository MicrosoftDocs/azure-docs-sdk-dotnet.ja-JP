<Type Name="AutoUserSpecification" FullName="Microsoft.Azure.Management.Batch.Models.AutoUserSpecification">
  <TypeSignature Language="C#" Value="public class AutoUserSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoUserSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.AutoUserSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoUserSpecification" />
  <TypeSignature Language="F#" Value="type AutoUserSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            バッチ サービスでタスクを実行する自動ユーザー用のパラメーターを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoUserSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoUserSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AutoUserSpecification クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoUserSpecification (Nullable&lt;Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt; scope = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; elevationLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt; scope, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; elevationLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoUserSpecification.#ctor(System.Nullable{Microsoft.Azure.Management.Batch.Models.AutoUserScope},System.Nullable{Microsoft.Azure.Management.Batch.Models.ElevationLevel})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional scope As Nullable(Of AutoUserScope) = null, Optional elevationLevel As Nullable(Of ElevationLevel) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.AutoUserSpecification : Nullable&lt;Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; -&gt; Microsoft.Azure.Management.Batch.Models.AutoUserSpecification" Usage="new Microsoft.Azure.Management.Batch.Models.AutoUserSpecification (scope, elevationLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scope" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt;" />
        <Parameter Name="elevationLevel" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt;" />
      </Parameters>
      <Docs>
        <param name="scope">自動ユーザーのスコープ</param>
        <param name="elevationLevel">自動ユーザー昇格レベル。</param>
        <summary>
            AutoUserSpecification クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElevationLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; ElevationLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; ElevationLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoUserSpecification.ElevationLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ElevationLevel As Nullable(Of ElevationLevel)" />
      <MemberSignature Language="F#" Value="member this.ElevationLevel : Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoUserSpecification.ElevationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="elevationLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または自動ユーザーの昇格のレベルを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            nonAdmin - 自動ユーザーは、管理者特権でのアクセス権のない標準ユーザーです。 管理 - 自動ユーザー昇格されたアクセス権を持つユーザーは、完全な管理者アクセス許可で操作を行います。 既定値は、nonAdmin です。 使用可能な値が含まれます: 'NonAdmin'、'Admin'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt; Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt; Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoUserSpecification.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As Nullable(Of AutoUserScope)" />
      <MemberSignature Language="F#" Value="member this.Scope : Nullable&lt;Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoUserSpecification.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、自動ユーザーのスコープ
            </summary>
        <value>To be added.</value>
        <remarks>
            プール - プール内の各ノードで作成される共通の自動ユーザー アカウントとしてタスクを実行するを指定します。 タスク - サービスがタスクの新しいユーザーを作成する必要がありますを指定します。 既定値はタスクです。 使用可能な値が含まれます 'Task'、'プール'。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>