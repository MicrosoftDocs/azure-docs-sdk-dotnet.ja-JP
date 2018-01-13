<Type Name="PipelineProperties" FullName="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties">
  <TypeSignature Language="C#" Value="public class PipelineProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PipelineProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class PipelineProperties" />
  <TypeSignature Language="F#" Value="type PipelineProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            パイプラインのプロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            PipelineProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineProperties (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Core.Models.Activity&gt; activities);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.Activity&gt; activities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactories.Core.Models.Activity})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (activities As IList(Of Activity))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Core.Models.Activity&gt; -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties" Usage="new Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties activities" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="activities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Core.Models.Activity&gt;" />
      </Parameters>
      <Docs>
        <param name="activities">To be added.</param>
        <summary>
            必須の引数で PipelineProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Activities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Core.Models.Activity&gt; Activities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.Activity&gt; Activities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.Activities" />
      <MemberSignature Language="VB.NET" Value="Public Property Activities As IList(Of Activity)" />
      <MemberSignature Language="F#" Value="member this.Activities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Core.Models.Activity&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.Activities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Core.Models.Activity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 パイプラインに属しているアクティビティ。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Datasets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Core.Models.Dataset&gt; Datasets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.Dataset&gt; Datasets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.Datasets" />
      <MemberSignature Language="VB.NET" Value="Public Property Datasets As IList(Of Dataset)" />
      <MemberSignature Language="F#" Value="member this.Datasets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Core.Models.Dataset&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.Datasets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Core.Models.Dataset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 パイプラインで定義されたアクティビティで使用されるデータセットの一覧。 このパイプラインに固有であり、datafactory 内で定義されていないデータセットを定義するために使用できます。 このパイプライン内で定義されているデータセットは、このパイプラインでのみ使用でき、共有することはできません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 項目の説明。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; End { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.End" />
      <MemberSignature Language="VB.NET" Value="Public Property End As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.End : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.End" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 パイプラインの終了時刻です。 開始および終了時間は両方とも空です。 パイプラインを作成するには両方が必要、パイプラインの有効期間の設定値を 1 つことはできません値を持ち、他のでない場合。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 パイプライン要求の処理のエラーです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ExpirationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpirationTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 パイプラインの作成後に、パイプラインが有効であり、プロビジョニングされた状態が維持される必要がある時間。 到達すると、有効期限があるない、アクティブな場合、または保留中の実行は、対応するパイプラインが自動的に削除されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HubName">
      <MemberSignature Language="C#" Value="public string HubName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.HubName" />
      <MemberSignature Language="VB.NET" Value="Public Property HubName As String" />
      <MemberSignature Language="F#" Value="member this.HubName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.HubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 このパイプラインが属しているハブの名前。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPaused">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsPaused { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsPaused" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.IsPaused" />
      <MemberSignature Language="VB.NET" Value="Public Property IsPaused As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsPaused : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.IsPaused" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 Pipline の状態です。 ブール値が設定されている場合、パイプラインは一時停止を true にします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineMode">
      <MemberSignature Language="C#" Value="public string PipelineMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.PipelineMode" />
      <MemberSignature Language="VB.NET" Value="Public Property PipelineMode As String" />
      <MemberSignature Language="F#" Value="member this.PipelineMode : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.PipelineMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 パイプラインのスケジューリングのメソッドが実行されます。 いずれかを指定する必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.PipelineMode" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 パイプラインのプロビジョニングの状態。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo RuntimeInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo RuntimeInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.RuntimeInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimeInfo As PipelineRuntimeInfo" />
      <MemberSignature Language="F#" Value="member this.RuntimeInfo : Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.RuntimeInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.PipelineRuntimeInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 パイプラインのランタイム情報。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Start { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.Start" />
      <MemberSignature Language="VB.NET" Value="Public Property Start As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Start : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineProperties.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 パイプラインの開始時刻です。 開始および終了時間は両方とも空です。 パイプラインを作成するには両方が必要、パイプラインの有効期間の設定値を 1 つことはできません値を持ち、他のでない場合。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>