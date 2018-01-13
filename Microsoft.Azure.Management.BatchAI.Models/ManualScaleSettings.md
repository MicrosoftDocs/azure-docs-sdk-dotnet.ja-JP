<Type Name="ManualScaleSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings">
  <TypeSignature Language="C#" Value="public class ManualScaleSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManualScaleSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ManualScaleSettings" />
  <TypeSignature Language="F#" Value="type ManualScaleSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クラスターの設定を手動でのスケーリングします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManualScaleSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ManualScaleSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManualScaleSettings (int targetNodeCount, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; nodeDeallocationOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 targetNodeCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; nodeDeallocationOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.#ctor(System.Int32,System.Nullable{Microsoft.Azure.Management.BatchAI.Models.DeallocationOption})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetNodeCount As Integer, Optional nodeDeallocationOption As Nullable(Of DeallocationOption) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings : int * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings (targetNodeCount, nodeDeallocationOption)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetNodeCount" Type="System.Int32" />
        <Parameter Name="nodeDeallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt;" />
      </Parameters>
      <Docs>
        <param name="targetNodeCount">クラスター内の計算ノードの目的の数。</param>
        <param name="nodeDeallocationOption">クラスター サイズが減少している場合は、コンピューティング ノードで実行されているジョブの処理方法を決定します。</param>
        <summary>
            ManualScaleSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDeallocationOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; NodeDeallocationOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; NodeDeallocationOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.NodeDeallocationOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeDeallocationOption As Nullable(Of DeallocationOption)" />
      <MemberSignature Language="F#" Value="member this.NodeDeallocationOption : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.NodeDeallocationOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeDeallocationOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、クラスターのサイズが減少している場合は、コンピューティング ノードで実行されているジョブの処理方法を決定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は requeue です。 使用可能な値が含まれます: 'requeue'、'終了'、'waitforjobcompletion'、'unknown'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetNodeCount">
      <MemberSignature Language="C#" Value="public int TargetNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TargetNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.TargetNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetNodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.TargetNodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.TargetNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターで目的のコンピューティング ノードの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は 0 です。 AutoScaleSettings が指定されていない場合は、このターゲットに、クラスターが開始します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="manualScaleSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
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