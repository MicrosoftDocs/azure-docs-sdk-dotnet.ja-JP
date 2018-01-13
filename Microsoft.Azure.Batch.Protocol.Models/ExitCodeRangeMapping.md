<Type Name="ExitCodeRangeMapping" FullName="Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping">
  <TypeSignature Language="C#" Value="public class ExitCodeRangeMapping" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitCodeRangeMapping extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitCodeRangeMapping" />
  <TypeSignature Language="F#" Value="type ExitCodeRangeMapping = class" />
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
            さまざまな終了コードをバッチ サービスが終了コードがその範囲内に応答する方法です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitCodeRangeMapping ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.#ctor" />
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
            ExitCodeRangeMapping クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitCodeRangeMapping (int start, int end, Microsoft.Azure.Batch.Protocol.Models.ExitOptions exitOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 start, int32 end, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions exitOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.#ctor(System.Int32,System.Int32,Microsoft.Azure.Batch.Protocol.Models.ExitOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping : int * int * Microsoft.Azure.Batch.Protocol.Models.ExitOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping" Usage="new Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping (start, end, exitOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
        <Parameter Name="exitOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
      </Parameters>
      <Docs>
        <param name="start">範囲内のコードを最初に終了します。</param>
        <param name="end">範囲の最後の終了コード。</param>
        <param name="exitOptions">バッチ サービスの応答方法 (包括) の末尾までの範囲の開始、終了コードでタスクが終了した場合。</param>
        <summary>
            ExitCodeRangeMapping クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public int End { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.End" />
      <MemberSignature Language="VB.NET" Value="Public Property End As Integer" />
      <MemberSignature Language="F#" Value="member this.End : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.End" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="end")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または範囲の最後の終了コードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions ExitOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions ExitOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.ExitOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitOptions As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.ExitOptions : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.ExitOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスク (包括) の末尾までの範囲の開始、終了コードが終了した場合、バッチ サービスの応答方法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public int Start { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.Start" />
      <MemberSignature Language="VB.NET" Value="Public Property Start As Integer" />
      <MemberSignature Language="F#" Value="member this.Start : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="start")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または範囲の最初の終了コードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="exitCodeRangeMapping.Validate " />
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