<Type Name="PropertyBatchResult" FullName="System.Fabric.PropertyBatchResult">
  <TypeSignature Language="C#" Value="public sealed class PropertyBatchResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PropertyBatchResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PropertyBatchResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PropertyBatchResult" />
  <TypeSignature Language="F#" Value="type PropertyBatchResult = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>結果を含むバッチを指定します、<see cref="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" />メソッドの呼び出しです。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FailedOperationException">
      <MemberSignature Language="C#" Value="public Exception FailedOperationException { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception FailedOperationException" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyBatchResult.FailedOperationException" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailedOperationException As Exception" />
      <MemberSignature Language="F#" Value="member this.FailedOperationException : Exception" Usage="System.Fabric.PropertyBatchResult.FailedOperationException" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>失敗した操作は、例外を取得します。 このパラメーターには、最初のためにスローされる例外が含まれています。 失敗した<see cref="T:System.Fabric.PropertyBatchOperation" />バッチ内のオブジェクト。</para>
        </summary>
        <value>
          <para><see cref="T:System.Exception" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailedOperationIndex">
      <MemberSignature Language="C#" Value="public int FailedOperationIndex { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FailedOperationIndex" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyBatchResult.FailedOperationIndex" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailedOperationIndex As Integer" />
      <MemberSignature Language="F#" Value="member this.FailedOperationIndex : int" Usage="System.Fabric.PropertyBatchResult.FailedOperationIndex" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>操作が失敗したインデックスを取得します。 このパラメーターは、失敗したのインデックスを含む<see cref="T:System.Fabric.PropertyBatchOperation" />バッチにします。</para>
        </summary>
        <value>
          <para><see cref="T:System.Int32" /> を返します。</para>
        </value>
        <remarks>
          <para>バッチ内の操作のいずれも失敗しなかった場合、このプロパティは-1 に設定することに注意してください。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty">
      <MemberSignature Language="C#" Value="public System.Fabric.NamedProperty GetProperty (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.NamedProperty GetProperty(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PropertyBatchResult.GetProperty(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProperty (index As Integer) As NamedProperty" />
      <MemberSignature Language="F#" Value="member this.GetProperty : int -&gt; System.Fabric.NamedProperty" Usage="propertyBatchResult.GetProperty index" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NamedProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><see cref="T:System.Int32" />が送信されたバッチでインデックスを示すです。</para>
        </param>
        <summary>
          <para>取得、<see cref="T:System.Fabric.NamedProperty" />によって返されるオブジェクト、<see cref="T:System.Fabric.PropertyBatchOperation" />指定したインデックスにします。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.NamedProperty" /> を返します。</para>
        </returns>
        <remarks>
          <para>なおかどうか<see cref="T:System.Fabric.NamedPropertyMetadata" />が返されますが依存、 <languagekeyword>includeValues</languagekeyword>への引数、<see cref="T:System.Fabric.GetPropertyOperation" />です。 指定されたよりも、この操作に別の種類と、エラーを返します。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>