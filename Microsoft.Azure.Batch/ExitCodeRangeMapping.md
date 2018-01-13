<Type Name="ExitCodeRangeMapping" FullName="Microsoft.Azure.Batch.ExitCodeRangeMapping">
  <TypeSignature Language="C#" Value="public class ExitCodeRangeMapping" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitCodeRangeMapping extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitCodeRangeMapping" />
  <TypeSignature Language="F#" Value="type ExitCodeRangeMapping = class&#xA;    interface ITransportObjectProvider&lt;ExitCodeRangeMapping&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            さまざまな終了コードをバッチ サービスの応答範囲の終了コードで、タスクが終了するかどうかは方法です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitCodeRangeMapping (int start, int end, Microsoft.Azure.Batch.ExitOptions exitOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 start, int32 end, class Microsoft.Azure.Batch.ExitOptions exitOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ExitCodeRangeMapping.#ctor(System.Int32,System.Int32,Microsoft.Azure.Batch.ExitOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ExitCodeRangeMapping : int * int * Microsoft.Azure.Batch.ExitOptions -&gt; Microsoft.Azure.Batch.ExitCodeRangeMapping" Usage="new Microsoft.Azure.Batch.ExitCodeRangeMapping (start, end, exitOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
        <Parameter Name="exitOptions" Type="Microsoft.Azure.Batch.ExitOptions" />
      </Parameters>
      <Docs>
        <param name="start">範囲内のコードを最初に終了します。</param>
        <param name="end">範囲の最後の終了コード。</param>
        <param name="exitOptions"><see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" /> Batch サービスがどのように対処する必要がありますかを指定する範囲の終了コードで、タスクが終了するかどうかは<see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" />に<see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.End" />包括的です。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public int End { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.End" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property End As Integer" />
      <MemberSignature Language="F#" Value="member this.End : int" Usage="Microsoft.Azure.Batch.ExitCodeRangeMapping.End" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            範囲の最後の終了コードを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            範囲は、包括的です。 たとえば場合、 <see cref="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" /> 8 と最後の 10 を起動し、8、9、10 の終了コードと一致することを指定します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions ExitOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions ExitOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExitOptions As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.ExitOptions : Microsoft.Azure.Batch.ExitOptions" Usage="Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、 <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" /> Batch サービスがどのように対処する必要がありますかを指定する範囲の終了コードで、タスクが終了するかどうかは<see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" />に<see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.End" />包括的です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public int Start { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Start As Integer" />
      <MemberSignature Language="F#" Value="member this.Start : int" Usage="Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            範囲の最初の終了コードを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            範囲は、包括的です。 たとえば場合、 <see cref="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" /> 8 と最後の 10 を起動し、8、9、10 の終了コードと一致することを指定します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>