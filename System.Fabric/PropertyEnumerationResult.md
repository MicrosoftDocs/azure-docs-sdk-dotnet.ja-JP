<Type Name="PropertyEnumerationResult" FullName="System.Fabric.PropertyEnumerationResult">
  <TypeSignature Language="C#" Value="public class PropertyEnumerationResult : System.Collections.ObjectModel.Collection&lt;System.Fabric.NamedProperty&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PropertyEnumerationResult extends System.Collections.ObjectModel.Collection`1&lt;class System.Fabric.NamedProperty&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PropertyEnumerationResult" />
  <TypeSignature Language="VB.NET" Value="Public Class PropertyEnumerationResult&#xA;Inherits Collection(Of NamedProperty)" />
  <TypeSignature Language="F#" Value="type PropertyEnumerationResult = class&#xA;    inherit Collection&lt;NamedProperty&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.ObjectModel.Collection&lt;System.Fabric.NamedProperty&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.Fabric.NamedProperty</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>プロパティ マネージャーによって、操作から返されるプロパティの列挙を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HasMoreData">
      <MemberSignature Language="C#" Value="public bool HasMoreData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasMoreData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.HasMoreData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasMoreData As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasMoreData : bool" Usage="System.Fabric.PropertyEnumerationResult.HasMoreData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>複数の残りのページがあることを示します。 
            <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult,System.TimeSpan,System.Threading.CancellationToken)" />次のページの取得を呼び出す必要があります。</para>
        </summary>
        <value>
          <para><see cref="T:System.Boolean" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBestEffort">
      <MemberSignature Language="C#" Value="public bool IsBestEffort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBestEffort" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.IsBestEffort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBestEffort As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBestEffort : bool" Usage="System.Fabric.PropertyEnumerationResult.IsBestEffort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>指定した名前で名前が、列挙中に変更されたかどうかを示します。 </para>
        </summary>
        <value>
          <para><see cref="T:System.Boolean" /> を返します。</para>
        </value>
        <remarks>
          <para>変更があった場合は、このプロパティは true です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsConsistent">
      <MemberSignature Language="C#" Value="public bool IsConsistent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsConsistent" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.IsConsistent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsConsistent As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsConsistent : bool" Usage="System.Fabric.PropertyEnumerationResult.IsConsistent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>指定した名前で、名前が、列挙中に変更されたかどうかを示します。 </para>
        </summary>
        <value>
          <para><see cref="T:System.Boolean" /> を返します。</para>
        </value>
        <remarks>
          <para>変更があった場合は、このプロパティは false です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsFinished">
      <MemberSignature Language="C#" Value="public bool IsFinished { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsFinished" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.IsFinished" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsFinished As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsFinished : bool" Usage="System.Fabric.PropertyEnumerationResult.IsFinished" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>これ以上の残りのページがあることを示します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Boolean" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsValid">
      <MemberSignature Language="C#" Value="public bool IsValid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsValid" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.IsValid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsValid As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsValid : bool" Usage="System.Fabric.PropertyEnumerationResult.IsValid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>列挙結果が有効かどうかを示します。 有効でない場合、結果を使用しません。</para>
        </summary>
        <value>
          <para><see cref="T:System.Boolean" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>