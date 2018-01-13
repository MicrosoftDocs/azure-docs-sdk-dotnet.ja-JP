<Type Name="AffinityInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.AffinityInformation">
  <TypeSignature Language="C#" Value="public class AffinityInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AffinityInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.AffinityInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class AffinityInformation" />
  <TypeSignature Language="F#" Value="type AffinityInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            タスクを開始するコンピューティング ノードを選択する、Batch service によって使用できる局所性のヒント。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AffinityInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AffinityInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AffinityInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AffinityInformation (string affinityId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string affinityId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AffinityInformation.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (affinityId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.AffinityInformation : string -&gt; Microsoft.Azure.Batch.Protocol.Models.AffinityInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.AffinityInformation affinityId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="affinityId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="affinityId">以前に実行するタスクまたはコンピューティング ノードの位置を表す不透明な文字列。</param>
        <summary>
            AffinityInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityId">
      <MemberSignature Language="C#" Value="public string AffinityId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AffinityInformation.AffinityId" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityId As String" />
      <MemberSignature Language="F#" Value="member this.AffinityId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AffinityInformation.AffinityId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="affinityId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定が以前に実行するタスクまたはコンピューティング ノードの位置を表す不透明な文字列。
            </summary>
        <value>To be added.</value>
        <remarks>
            このタスクがそのコンピューティング ノードで実行する必要があることを示すためにコンピューティング ノードの affinityId を渡すことができます。 これはソフト アフィニティだけであることに注意してください。 ターゲット ノードがビジー状態、またはタスクのスケジュール時に使用できない、タスクがスケジュールされる他の場所。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AffinityInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="affinityInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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