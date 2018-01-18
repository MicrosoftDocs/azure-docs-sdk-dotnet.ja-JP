<Type Name="ShardManagementException" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementException">
  <TypeSignature Language="C#" Value="public sealed class ShardManagementException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ShardManagementException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ShardManagementException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type ShardManagementException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1032:ImplementStandardExceptionConstructors", Justification="There is no valid default ErrorCategory/ErrorCode that makes sense. This is akin to SqlException")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="de071-101">記憶域操作中に発生する例外の表現。</span><span class="sxs-lookup"><span data-stu-id="de071-101">Representation of exceptions that occur during storage operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ErrorCategory">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCategory ErrorCategory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCategory ErrorCategory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementException.ErrorCategory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCategory As ShardManagementErrorCategory" />
      <MemberSignature Language="F#" Value="member this.ErrorCategory : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCategory" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementException.ErrorCategory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCategory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de071-102">エラー カテゴリ。</span><span class="sxs-lookup"><span data-stu-id="de071-102">Error category.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementException.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As ShardManagementErrorCode" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementException.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de071-103">エラー コード。</span><span class="sxs-lookup"><span data-stu-id="de071-103">Error code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="shardManagementException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="de071-104">データを設定する SerializationInfo です。</span><span class="sxs-lookup"><span data-stu-id="de071-104">The SerializationInfo to populate with data.</span></span></param>
        <param name="context"><span data-ttu-id="de071-105">宛先 (StreamingContext を参照してください) このシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="de071-105">The destination (see StreamingContext) for this serialization.</span></span></param>
        <summary>
            <span data-ttu-id="de071-106">ターゲット オブジェクトをシリアル化に必要なデータに、SerializationInfo を設定します。</span><span class="sxs-lookup"><span data-stu-id="de071-106">Populates a SerializationInfo with the data needed to serialize the target object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>